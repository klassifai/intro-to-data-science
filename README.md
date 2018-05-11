# intro-to-data-science
Code for a gentle nudge into data science

This repository contains notebooks and data folders for 3 projects, which will help you get acquainted with data science.

# Setup

You need to install [Miniconda](https://conda.io/miniconda.html) or [Anaconda](https://www.anaconda.com/download) for basic setup

Once you have those two set up, you can copy the environment needed for this project with this command:
`conda env create -f environment.yml`

# Running a notebook

Once you create the environment, you can activate it with `source activate intro_env` on *nix machines or `activate intro_env`
on Windows machines.

To start the Jupyter server, you can type `jupyter notebook` at the root of the repository, and this will start a server on port
8888 by default. Open a browser, type `http://localhost:8888` and voila! Your notebooks are ready to be run
