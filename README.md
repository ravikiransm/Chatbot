# Chatbot
## Chatbot Startkit in TensorFlow 1.4
### The example on how to implement simple chatbot using seq2seq model in the python using tensorflow 1.4 version. This Chatbot example shows the attention mechanism and bucketing as well.

# Dataset
## I've used the Cornell Movie Dialogs corpuse for this example. 
   
# Install
    Supported Python version
         - Python version used in this project: 3.5+
         
# Libraries used
### Pandas 0.18.0
### Numpy 1.10.4
### TensorFlow 1.4.0

# Code

### The core seq2seq model functions are all insude model_utils.py.

### Data preprocessing and NLP functions are inside cornell_data_utils.py.

### If you want to play with models hyperparameters use config.py.

# Run

### To run this project you will need some software, like Anaconda, which provides support for running .ipynb files (Jupyter Notebook).

### After making sure you have that, you can run from a terminal or cmd next lines:

     ipython notebook chatbot.ipynb

## or

    jupyter notebook chatbot.ipynb
