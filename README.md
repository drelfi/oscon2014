# Introduction

This is the presentation given by Chad Naber and David Elfi at OSCON 2014 called
["Big Data Analysis 0-60 in 90 days"](http://www.oscon.com/oscon2014/public/schedule/detail/34407)

This presentation is based on IPython Notebook and needs to be built before using it.
It also includes a precompiled version for a quick access.

# Building it

The stack for build it requires:
* IPython[notebook] 2.1.0
* nbconvert
* Matplotlib
* Numpy
* Scipy
* scikit-learn
* pydot

Once the python packages are installed, the command to create a new version is:
```
ipython nbconvert --to slides OSCON\ \'14\ -\ Big\ Data\ 0-60\ in\ 90\ days.ipynb
```

# Running it

For running it, there are 2 options:

* Open the .html file in a browser
* Run `python -m SimpleHTTPServer 9999` and open a browser at http://localhost:9999

