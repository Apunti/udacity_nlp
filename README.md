# Introduction
This repository contains the projects of Udacity's [Natural Language Processing
Nanodegree](https://www.udacity.com/course/natural-language-processing-nanodegree--nd892).

# Projects

1. **HMM Tagger**: use hidden markov model to train a POS tagger.
2. **Machine Translation**: build and train a deep neural network model for English to French translation.
3. **Speech Recognition**: build and train a deep neural network model for end-to-end
automatic speech recognition (ASR) with the LibriSpeech dataset.

# Installation
The python packages you will be needing are:
- jupyter
- matplotlib
- nltk
- pandas
- pomegranate
- keras
- tensorflow
- python_speech_features
- librosa

I would recommend to create a virtual environment and installing them via if you are working
with Linux (assuming you have python 3, pip and virtualenv installed, check [here](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/) instead):

```
python3 -m venv env
source env/bin/activate
python -m pip install -r requirements.txt
```
Once you have installed all the dependencies you should be able to run the notebooks.
Please, refer to the README of speech_recognition for further installation guides.
