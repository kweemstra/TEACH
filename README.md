# Active learning session created for the UTQ module TEACH
Created by Cornelis Weemstra

## When and where

- **Date:** 29 March 2019
- **Time:** 09:00hr

## Geting ready

This will be an active learning assignment, which will make use of the python programming language in combination with [Jupyter Notebooks](https://jupyter.org/), which you should install (or already have) on your laptops that you bring to the course.

We have prepared some instructions for setting up your environment so that you come prepared and so that we don’t spend precious time on these preparations during the assignment. Please follow the instructions. These instructions should work on Linux, macOS, and Windows.



1. Download Miniconda:
Miniconda is a mini version of Anaconda that includes only conda and its dependencies. Follow the installation instruction (Linux, OSX or macOS) to get started on your system.

In short, this will include:

Downloading the Miniconda3-latest-*-x86_64.sh, where * will be either MacOSX or Linux.
Installing miniconda by firing up the Terminal and typing:
cd Downloads/
bash Miniconda3-latest-*-x86_64.sh
Agreeing to the license terms (type yes)
Accept the default install location proposed by the installer (press Enter)
Allow Miniconda to prepend the install location to the PATH (type yes)


---
**Step 1:**

If you do not already have Anaconda or Miniconda installed on your machine (Hint: If you are unsure, go ahead and install a fresh copy), follow this link to download Miniconda and install the right package for your OS (Windows, Linux, or MacOS): 

https://conda.io/en/latest/miniconda.html

We recommend the 64-bit Python 3.7 version regardless of your OS. Installation should be straightforward (choose default install location), but will inlude agreeing to the license terms (mark/type `yes').



---
**Step 2:**

Whether you just installed Miniconda or are using an already existing conda environment, create a new environment by typing the following command in you terminal ('Anaconda Prompt' on Windows):

```shell
conda create -n ctg -c conda-forge -y python=3.7
```

And activate this new environment with:

```shell
conda activate ctg
```

---
**Step 3:**

Now install the packages needed to run the course notebooks with the following command:

```shell
conda config --add channels conda-forge && conda install -y ipython \
    tornado=5.1.1 jupyter notebook ipywidgets numpy scipy numba pandas \
    gdal netcdf4 matplotlib basemap basemap-data-hires pillow obspy
```

---

*See you this Thursday,*
Kees

# [Download the notebooks](http://tinyurl.com/y4aehjc5) http://tinyurl.com/y4aehjc5
