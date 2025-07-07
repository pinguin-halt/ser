# Speech Emotion Recognition

### Introduction

- This repository handles building and training Speech Emotion Recognition System.
- The basic idea behind this tool is to build and train/test a suited machine learning ( as well as deep learning ) algorithm that could recognize and detects human emotions from speech.
- This is useful for many industry fields such as making product recommendations, affective computing, etc.
  
### 📌 Keywords
- Speech Emotion Recognition
- 1D CNN
- Channel Attention
- Spatial Attention
- MFCC Features
- Data Augmentation
-  SAVEE
-  RAVDESS
-  CREMA-D
-  TESS
-  EMO-DB
-  EMOVO

## Requirements
- **Python 3.8+**
### Python Packages
- **Tensorflow**
- **librosa==0.6.3**
- **numpy**
- **pandas**
- **scikit-learn==0.24.2**
- **tqdm==4.28.1**
- **matplotlib==2.2.3**

### Dataset
This repository used 6 datasets including RAVDESS, TESS, SAVEE, EMO-DB, CREMA-D, and EMOVO.
I have provided the link for downloading the datasets 
- [**RAVDESS**](https://www.kaggle.com/code/shivamburnwal/speech-emotion-recognition)
- [**CREMA-D**](https://www.kaggle.com/datasets/ejlok1/cremad)
- [**SAVEE**](https://www.kaggle.com/datasets/ejlok1/surrey-audiovisual-expressed-emotion-savee)
- [**TESS**](https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess)
- [**EMOVO**](https://www.kaggle.com/datasets/sourabhy/emovo-italian-ser-dataset)
- [**EmoDB**](https://www.kaggle.com/datasets/piyushagni5/berlin-database-of-emotional-speech-emodb)
## Model Archietecture
![](images/joomla_speech_prosody.png?raw=true)
## Feature Extraction
Feature extraction is the main part of the speech emotion recognition system. It is basically accomplished by changing the speech waveform to a form of parametric representation at a relatively lesser data rate
In this repository, we have used the following features
- MFCC
- Chorma
## Installation

To run the code, follow these steps:

Clone the repository 

```
git@github.com:spilabkorea/ser.git
```
Install the libraries by the following command
```
conda env create -f environment.yml
```
features extraction

To extract the MFCC and Chroma features run
```
preprocessing files
```
Train the models
for the model trainining run the training scripts


