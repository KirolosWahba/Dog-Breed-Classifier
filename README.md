# Udacity MLND Capstone Project Dog Breed Classifier


## Project description

In this project I developed a CNN for the recognition of dog breeds.
Based on a picture of a dog, an algorithm will give an estimate of the breed of the dog.
If the image of a person is given, the algorithm should reproduce the most similar dog breed.

## Requirements

This project was done on a Linux-OS ([Ubuntu 19.10](https://ubuntu.com/download/desktop)) with an [Anaconda distribution](https://www.anaconda.com/).

> Anaconda is a free and open-source distribution of the Python and R programming languages for scientific computing (data science, machine learning > > applications, large-scale data processing, predictive analytics, etc.)
> [Wikipedia](https://en.wikipedia.org/wiki/Anaconda_(Python_distribution))

To start directly with the correct requirements for Anaconda I have added a file called environment.yml to the repo. You can create a
[conda virtual environment](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) with this file:

```bash
conda env create -f environment.yml
```

The first line of the yml file sets the new environment's name.
And then you can activate this new environment:

```bash
conda activate envmlcv
```

If you do not want to use the environment.yml to create a new virtual environment then you need to install with the command `conda install ...` the following packages:

```bash
numpy
glob
pandas
opencv
matplotlib
tqdm
torch
torchvision
PIL
```

When all dependencies are installed, you can start the Jupyter Notebook `dog_app.ipynb` with this evironment and take off.

## Explanation in depth

If you want to know more about the project then have a look at my project report `report.pdf` and the Juypter Notebook `dog_app.ipynb`.

