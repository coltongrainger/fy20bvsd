# Boulder Valley School District Mentoring Project

## TODO

This is a reverse chronological TODO list. Please feel free to add notes/comments.

### 2020-01-07

Suchit! Here are two tasks for the next week or so.

#### 1. Test the metadata ingest and note any errors.

Most importantly, I've released a prototype of the metadata ingest system. Can you break it? That is, try cloning the repository

<https://github.com/coltongrainger/rdai>

and running through the notebook

[`uscg-storis.ipynb`](https://github.com/coltongrainger/rdai/blob/master/uscg-storis.ipynb)

on your system, then keeping note of what cells throw error messages. Our next check-in I will ask for a brief summary of the errors you ran into, and how you were able to circumvent them.


Right away, I should note you'll need to install, either with `conda` or `pip`, a few dependencies, including `python-magic`, and maybe others. (I'm quite ignorant when it comes to python environments and dependency management: Asking you to install packages "by hand" is *not the right way to do things*.)

The goals for this task are

- to download a sample set of images, 
- to create a `json` roster of the images in the `out` directory, and 
- to rename the images according to their `uuid`.

#### 2. Do a quick refresher on how to munge data with pandas.

I've reorganized the notebooks in this repository according to my favorite *stable naming convention for literature*, which is 

```
<year>-<author>-<title>.<extension>
```

because such files can be stored in the same directory without too much namespace conflict, and it makes citing one's work later on a bit easier.

Here are the notebooks we've worked through so far:

- [`2016-kuleshov-python-numpy-tutorial.ipynb`](https://github.com/coltongrainger/fy20bvsd/blob/master/2016-kuleshov-python-numpy-tutorial.ipynb)
- [`2015-dlab-introduction-workshop.ipynb`](https://github.com/coltongrainger/fy20bvsd/blob/master/2015-dlab-introduction-workshop.ipynb) (this version is my working copy)

Can you do a brief review of the operations in `numpy` and `pandas` that are displayed in both of these notebooks?

Concurrently, let's take a look at a similar, more recent, tutorial from Chris Fonnesbeck (referenced in the DLab tutorial):

- `2017-fonnesbeck-1_Data_Preparation.ipynb`

The Lunacek tutorials (e.g., those files `2019-lunacek*.ipynb`) have powergrid data from NREL, which might be of interest to you if you are comfortable with the three notebooks above.

The goals for this task are to be proficient at indexing, slicing, reshaping, copying, and otherwise mutating 

1. numpy arrays and 
2. pandas DataFrames.

#### coming up

I have a supervision meeting on Thursday 2020-01-09. After it, I will decide whether our next step is to work towards a MySQL injection of image metadata with pandas or towards image file manipulation and classification with numpy/scipy.

### 2019-12-20

The first goal should be to have enough proficiency with pandas to be able to load DataFrames from .json files that are

- lists of dictionaries

where the keys to the dictionaries are *unique* field names, such as, "document.id_within_archive" and "archive.host_country".

The second goal should be to have enough proficiency with `exiftool` to be able to distinguish between 

- two non-identical images.

A third goal is to be able to recognize

- two identical images with the same "ImageUniqueID" 

where "ImageUniqueID" can be read by `exiftool` a la `exiftool -ImageUniqueID image.jpg` and is given by 32 character hexadecimal string.

### 2019-11-06

Hi Suchit! Please excuse me for taking a few weeks to follow up since our last video chat. Here is a short list of technical tasks (leading up to an introduction to Numpy in Python) for you to complete in, say, the next 14 days.

#### setup version control

- Install [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) for your operating system.
- Apply for a [github student developer account](https://help.github.com/en/github/teaching-and-learning-with-github-education/applying-for-a-student-developer-pack) (this takes only a day or two).
- [Fork](https://help.github.com/en/github/getting-started-with-github/fork-a-repo) this repository to your own github account, then [clone](https://git-scm.com/book/en/v1/Git-Basics-Getting-a-Git-Repository) your fork of this repository onto your operating system.

#### setup a scientific computing environment

- Install [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html) for your operating system.
- Open the `kuleshov` tutorial by running `jupyter-notebook` in a [terminal](https://tutorial.djangogirls.org/en/intro_to_command_line/) in the directory that is your fork of this git repository on your operating system. There's a Graphic User Interface for the Jupyter Notebook in  your browser from which you can start the tutorial.
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

