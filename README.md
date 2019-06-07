# Machine-Translation-AI
# Introduction
In this notebook, we will build a deep neural network that functions as part of an end-to-end machine translation pipeline. Our completed pipeline will accept English text as input and return the French translation.

# Setup

This project requires GPU acceleration to run efficiently. Support is available to use AWS for accessing GPU-enabled cloud computing resources.

## Amazon Web Services

Please refer to the instructions for setting up a GPU instance for this project, and refer to the project instructions I will post later for setup. The recommended AMI should include compatible versions of all required software and libraries to complete the project.

## Install
- Python 3
- NumPy
- TensorFlow 1.x
- Keras 2.x

## Converting to HTML

There are several ways to generate an HTML copy of the notebook:

 - Running the last cell of the notebook will export an HTML copy

 - Navigating to **File -> Download as -> HTML (.html)** within the notebook

 - Using `nbconvert` from the command line

    $ pip install nbconvert
    $ nbconvert machine_translation.ipynb
