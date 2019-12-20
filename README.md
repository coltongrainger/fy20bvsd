# Boulder Valley School District Mentoring Project

## TODO

This is a reverse chronological TODO list. Please feel free to add notes/comments.

### 2019-12-20

The first goal should be to have enough proficiency with pandas to be able to load DataFrames from .json files that are

- lists of dictionaries

where the keys to the dictionaries are *unique* field names, such as, "document.id_within_archive" and "archive.host_country".

The second goal should be to have enough proficiency with `exiftool` to be able to distinguish between 

- two non-identical images.

A third goal is to be able to recognized

- two identical images with the same "ImageUniqueID" 

where "ImageUniqueID" can be read by `exiftool` a la `exiftool -ImageUniqueID image.jpg` and is given by 32 character hexadecimal string.

> # pandas
> 
> Materials for teaching the introductory pandas workshop at UC Berkeley's D-Lab.
> 
> ## Set Up
> 
> For this workshop we'll be using a Jupyter notebook.
> 
> ### Software for the workshop
> 
> The best learning experience happens when you can edit and run code. So, please have pandas, Matplotlib, and Jupyter or IPython installed. There are several options for getting your environment set up.
> 
> 1. [Anaconda](http://continuum.io/downloads) with Python 3.5+ (2.7 is okay).
> 2. Python 3.5+ (2.7 is okay) and required packages installed using a package manager, such as `conda` (via [Miniconda](https://conda.io/docs/install/quick.html)) or [pip](https://pip.pypa.io/en/stable/installing.html); you must install IPython 3.0+ with notebook support or IPython 4.0+/Jupyter 1.0+, pandas 0.17+, and Matplotlib 1.3+.
> 3. (Perhaps as a last resort) [BCE Summer 2015](http://bce.berkeley.edu/install.html).
> 
> Both Anaconda and BCE distributions will install everything you need for this workshop (but BCE will most likely be out of date). If you decide to use `pip`, you can do the following (or for Miniconda, replace `pip` with `conda`):
> 
> ```
> # Install pandas and Matplotlib
> $ pip install pandas matplotlib
> 
> # Install Jupyter
> $ pip install --upgrade jupyter
> ```
> 
> ### Files for the workshop
> 
> Once those are installed, you should get the necessary files for this workshop, which are contained in this repository. Get them by doing the following:
> 
> ```
> # Clone this repository
> $ git clone https://github.com/dlab-berkeley/introduction-to-pandas.git
> 
> # Navigate to the repo
> $ cd introduction-to-pandas
> 
> # Start the interactive session
> $ jupyter notebook
> 
> # ...alternatively (older versions of IPython)
> $ ipython notebook
> ```
> 
> ## Outline
> 
> For this workshop, we'll go through an example using European unemployment data. We'll load, view, and modify the data as well as calculate some descriptive statistics. The idea is to get a sense of what it would be like to use pandas as part of your workflow.
> 
> We plan to cover:
> 
> * pandas data structures
> * loading data
> * subsetting and filtering
> * calculating summary statistics
> * dealing with missing values
> * merging data sets
> * creating new variables
> * basic plotting
> * exporting data
> 
> ## Further resources
> 
> [pandas Documentation](http://pandas.pydata.org/pandas-docs/stable/)

### 2019-11-06

Hi Suchit! Please excuse me for taking a few weeks to follow up since our last video chat. Here is a short list of technical tasks (leading up to an introduction to Numpy in Python) for you to complete in, say, the next 14 days.

#### setup version control

- Install [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) for your operating system.
- Apply for a [github student developer account](https://help.github.com/en/github/teaching-and-learning-with-github-education/applying-for-a-student-developer-pack) (this takes only a day or two).
- [Fork](https://help.github.com/en/github/getting-started-with-github/fork-a-repo) this repository to your own github account, then [clone](https://git-scm.com/book/en/v1/Git-Basics-Getting-a-Git-Repository) your fork of this repository onto your operating system.

#### setup a scientific computing environment

- Install [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html) for your operating system.
- Open [this tutorial](https://github.com/coltongrainger/fy20bvsd/blob/master/2019-11-06-kuleshov-python-numpy-tutorial.ipynb) by running `jupyter-notebook` in a [terminal](https://tutorial.djangogirls.org/en/intro_to_command_line/) in the directory that is your fork of this git repository on your operating system. There's a Graphic User Interface for the Jupyter Notebook in  your browser from which you can start the tutorial.
- Work through a few sections of that tutorial (at least until you get to the definition of arrays). 
- Please come up with a list of 5 to 10 questions about numpy and python for our next videochat.

#### ask for help by opening git issues

Thanks! Please let me know if you have any questions about these instructions.

1. You can either email me or, preferably,
2. open an [issue](https://github.com/coltongrainger/fy20bvsd/issues) in this git repo.

### 2019-10-03

- familiarize yourself with NCAR <https://en.wikipedia.org/wiki/National_Center_for_Atmospheric_Research>
- familiarize yourself with CISL <https://www2.cisl.ucar.edu/org/about>
- watch Philip Brohan's CISL seminar talk <https://www.youtube.com/watch?v=O98ha2c4vGs>
- watch my SIParCS seminar talk <https://www.youtube.com/watch?v=wURNDpfBS4Q>

