# More on Machine Learning & Deep Learning

Find more of my deep learning models on the following links:

- [Car Detection](https://github.com/Rakib1508/car-detection)
- [Emoji Generator](https://github.com/Rakib1508/emojify)
- [Face Recognition](https://github.com/Rakib1508/face-recognition)
- [Machine Translation](https://github.com/Rakib1508/machine-translation)
- [Neural Style Transfer](https://github.com/Rakib1508/neural-style-transfer)
- [Trigger Word Detection](https://github.com/Rakib1508/trigger-word-detection)
- [Word Vector Representation](https://github.com/Rakib1508/word-vector-representation)

More ML/DL models in the following links:

- [Simple Deep Learning models](https://github.com/Rakib1508/dl-projects)
- [Machine Learning with MatLab](https://github.com/Rakib1508/Machine-Learning)

# Machine Learning (ML)

This repositry contains the python solutions of the programming assignments for the [Coursera Machine Learning online class](https://www.coursera.org/learn/machine-learning) taught by Professor Andrew Ng. This is perhaps the most popular introductory online machine learning class. In addition to being popular, it is also one of the best Machine learning classes any interested student can take to get started with machine learning. An unfortunate aspect of this class is that the programming assignments are in MATLAB or OCTAVE, probably because this class is quite old and was probably made before python became the go-to language in machine learning.

My MATLAB solutions can also be found in my [Machine Learning Repository](https://github.com/Rakib1508/Machine-Learning) which I have updated in the past on my profile.

The Python machine learning ecosystem has grown exponentially in the past few years, and is still gaining momentum. I also wanted to get my hands dirty using Python to build ML models. This is why I decided to use the datasets from the course assignments and build my own models using Python libraries on Jupyter Notebook platform.

- The assignments use [Jupyter Notebook](http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html), which provides an intuitive flow easier than the original MATLAB/OCTAVE assignments.
- The original assignment instructions have been modified according to needs.
- The re-written instructions are now embedded within the Jupyter Notebook. For each assignment, all work is done solely within the notebook.

## Downloading the Assignments

To get started, you can start by either downloading a zip file of these assignments by clicking on the `Clone or download` button. If you have `git` installed on your system, you can clone this repository using :

    git clone https://github.com/Rakib1508/ml-projects.git

Each assignment is contained in a separate folder. For example, assignment 1 is contained within the folder `project_1_"model_name"`. Each project contains:

- The assignment `jupyter` notebook, which has a `.ipynb` extension. All the code which you need to write will be written within this notebook.
- Datasets used to build that model, in some models initial weights are also provided. Depending on the projects, there can be other files as well.
- Figures generated from the model are saved in a folder named `plots` in most of the projects.

## Requirements

These assignments has been tested and developed using the following libraries:

    - python==3.9.4
    - numpy==1.20.0
    - scipy==1.6.3
    - matplotlib==3.4.2
    - jupyter==6.4.0
    - jupyter-client==6.1.12

We recommend using at least these versions of the required libraries or later. Python 2 is not supported.

## Python Installation

We highly recommend using anaconda for installing python. [Click here](https://www.anaconda.com/download/) to go to Anaconda's download page. Make sure to download Python 3.9 version.
If you are on a windows machine:

- Open the executable after download is complete and follow instructions.
- Once installation is complete, open `Anaconda prompt` from the start menu. This will open a terminal with python enabled.

If you are on a linux machine:

- Open a terminal and navigate to the directory where Anaconda was downloaded.
- Change the permission to the downloaded file so that it can be executed. So if the downloaded file name is `Anaconda3-5.1.0-Linux-x86_64.sh`, then use the following command:

  `chmod a+x Anaconda3-5.1.0-Linux-x86_64.sh`

- Now, run the installation script using `./Anaconda3-5.1.0-Linux-x86_64.sh`, and follow installation instructions in the terminal.

Once you have installed python, create a new python environment will all the requirements using the following command:

    conda env create -f environment.yml

After the new environment is setup, activate it using (windows)

    activate machine_learning

or if you are on a linux machine

    source activate machine_learning

Now we have our python environment all set up, we can start working on the assignments. To do so, navigate to the directory where the assignments were installed, and launch the jupyter notebook from the terminal using the command

    jupyter notebook

This should automatically open a tab in the default browser. To start with assignment 1, open the notebook `./Exercise1/exercise1.ipynb`.
