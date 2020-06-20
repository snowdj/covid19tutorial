# COVID-19 Data Tutorials

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sswatson/covid19tutorial/master?filepath=covid19bayesian.ipynb)

This repo contains resources for the third COVID-19 Data Tutorial, hosted by Samuel Watson with the Data Science Initiative at Brown University on the 19th of June, 2020.

1. **Computational notebook environment**. You can click the Binder badge above to launch a notebook in your browser for performing the calculations yourself in a Jupyter notebook.

2. **Pluto notebook**. The file `covid19bayesian.jl` is a [Pluto](https://github.com/fonsp/Pluto.jl) notebook. Pluto is like a lightweight version of Jupyter, and its main distinguishing feature is that dependencies between code cells are tracked automatically and used to propagate any changes you make to the notebook (like Excel, but for a whole notebook!). 

  If you want to use the Pluto notebook, [download Julia](https://julialang.org/downloads/), type `julia` at the command line, type in `]add Pluto` and press enter. Once the package manager does its thing, run `import Pluto` in your Julia session and then `Pluto.run(1234)`. Then visit `http://localhost:1234` in either Firefox or Chrome (it does not work with Safari). Download this repo and type the file path of the file `covid19bayesian.jl` into the input field that the Pluto notebook landing page provides.
  
3. **Jupyter notebook**. For convenience, a Jupyter version is included as well. This notebook can be executed in the cloud using the above-mentioned Binder link, or you can download it and run it locally.

4. **Pluto notebook preview.** If you want to see what the Pluto notebook looks like, check out `covid19bayesian.html`. You'll want to copy the whole repo and view this file locally, since the HTML file needs to be in the same directory as the folder `covid19bayesian_files`.

![](https://raw.githubusercontent.com/sswatson/covid19tutorial/master/rt-and-cases.png)