# HMM-Part-of-Speech-Tagger

Hidden Markov Model based Parts of Speech Tagger using the Pomegranate library.

## Introduction

In this notebook, [Pomegranate](https://github.com/jmschrei/pomegranate) library is used to build a hidden Markov model for part of speech tagging with a [universal tagset](http://www.petrovi.de/data/universal.pdf).

Alternatively, you can download a copy of the project from GitHub and then run a Jupyter server locally with [Anaconda](https://www.anaconda.com/download/).

1. Open a terminal and clone the project repository:

```
$ git clone https://github.com/udacity/artificial-intelligence
```

2. Switch to the project folder and create a conda environment (note: you must already have Anaconda installed):

```
$ cd "artificial-intelligence/Projects/4_HMM Tagger"
.../ $ conda env create -f hmm-tagger.yaml
```

3. Activate the conda environment, then run the jupyter notebook server. (Note: windows users should run `activate hmm-tagger`)

```
.../ $ source activate hmm-tagger
(hmm-tagger) .../ $ jupyter notebook
```

Depending on your system settings, Jupyter will either open a browser window, or the terminal will print a URL with a security token. If the terminal prints a URL, simply copy the URL and paste it into a browser window to load the Jupyter browser. Once you load the Jupyter browser, select the project notebook (HMM tagger.ipynb) and follow the instructions inside to complete the project.
