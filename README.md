# Numeric Digit Classification


TensorFlow implementation of a deep CNN (Convolutional Neural Network) for classifying numeric digits.



## Table of Contents


* Data
* Viewing and Running the Notebook
* Shutdown
* License



## Data


Datasets originate from the [MNIST](http://yann.lecun.com/exdb/mnist/) database of handwritten digits, which consists of 60,000 training examples and 10,000 testing examples. In the main Jupyter notebook, `numeric_digit_classification.ipynb`, the tensorflow.examples module downloads the raw data and imports them into python as numpy arrays. Of the 60,000 original training examples, 5,000 are set aside for validation.



## Viewing and Running the Notebook


1. Make sure you have conda installed and reconstruct the environment as follows.  
`$ conda env create -f conda_environment.yml  `  
`$ source activate numeric-digit-classification`

2. Serve the jupyter notebook.  
`$ jupyter notebook numeric_digit_classification.ipynb`

3. View and/or run the notebook in your webbrowser at `http://localhost:8888/`, or some increment of that port if you already have other notebooks running.



## Shutdown

1. Close the browser tab where the jupyter notebook is open.

2. Stop the notebook server by pressing ctrl+c in the terminal session where you started it.

3. Deactivate the conda environment.  
`$ source deactivate`



## License

MIT License

Copyright (c) 2017 Karl J. Obermeyer

See LICENSE.md for details.