# Python Notes

This repository contains a collection of notes on Python using Jupyter Notebooks. These Notes will teach you the following:
 - Basics of Python 
 - Python scripting and plotting
 - System interface, data manipulation, file I/O
 - Introduction to NumPy
 - Intro to NumPy and SciPy

These notes are used in the scientific-programming Module of AMS 561 - Introduction to Computational Science at Stony Brook University.

To run these notebooks interactively, you need to set up some software packages on your computer. First, install Docker for your platform (Windows, MacOS, Linux, cloud platforms, etc.), follow the instructions at [docker.com](https://docs.docker.com/engine/getstarted/step_one/). Then, download this repository and start Jupyter Notebook using the command `docker-notebook` script in the directory. For example, to open `IntroductionToNumPy.ipynb.ipynb`, use the following command in a terminal:
```
    ./docker-notebook IntroductionToNumPy.ipynb
```
It will automatically download the Docker image, start Jupyer Notebook in the image, and open the notebook your web browser for you to run interactively.

**Note**: The Docker image is about 500 MB, so you need to have a faster internet connection to download the image for the first time. The `docker-notebook` script does not support Docker Toolbox on Windows.