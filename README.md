# Speech Emotion Recognition

### Introduction

🎙️ Speech Emotion Recognition (SER) using MFCCs and 1D-CNN with attention mechanisms.
🚀 Achieves state-of-the-art accuracy across six benchmark datasets (SAVEE, RAVDESS, TESS, etc.).
🧠 Robust, generalizable, and optimized for real-world human-computer interaction and assistive tech.


![](figure/archietecture.png?raw=true)

# Highlights 🎯
We focused on high-accuracy multilingual speech recognition, speech emotion recognition. Trained on six benchmark datasets and achieved state-of-the-art performance compared to previous speech emotion recognition models on the same datasets. 
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

### Benchmark Datasets 📝
We performed the epxeriments on six benchmark dataset. The download link for these datasets in given below. 
- [**RAVDESS**](https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio) contains 1440 files: 60 trials per actor x 24 actors = 1440. The RAVDESS contains 24 professional actors (12 female, 12 male), vocalizing two lexically-matched statements in a neutral North American accent. Speech emotions includes calm, happy, sad, angry, fearful, surprise, and disgust expressions. Each expression is produced at two levels of emotional intensity (normal, strong), with an additional neutral expression.
- [**CREMA-D**](https://www.kaggle.com/datasets/ejlok1/cremad) contains 7,442 original clips from 91 actors. These clips were from 48 male and 43 female actors between the ages of 20 and 74 coming from a variety of races and ethnicities (African America, Asian, Caucasian, Hispanic, and Unspecified). Actors spoke from a selection of 12 sentences. The sentences were presented using one of six different emotions (Anger, Disgust, Fear, Happy, Neutral, and Sad) and four different emotion levels (Low, Medium, High, and Unspecified).
- [**SAVEE**](https://www.kaggle.com/datasets/ejlok1/surrey-audiovisual-expressed-emotion-savee) recorded from four native English male speakers (identified as DC, JE, JK, KL), postgraduate students and researchers at the University of Surrey aged from 27 to 31 years. Emotion has been described psychologically in discrete categories: anger, disgust, fear, happiness, sadness and surprise. A neutral category is also added to provide recordings of 7 emotion categories.
- [**TESS**](https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess) contains 200 target words were spoken in the carrier phrase "Say the word _' by two actresses (aged 26 and 64 years) and recordings were made of the set portraying each of seven emotions (anger, disgust, fear, happiness, pleasant surprise, sadness, and neutral). There are 2800 data points (audio files) in total.
- [**EMOVO**](https://www.kaggle.com/datasets/sourabhy/emovo-italian-ser-dataset) is first emotional corpus applicable to the Italian language. It is a database built from the voices of 6 actors (3 males and 3 females) who played 14 sentences simulating 6 emotional states (disgust, fear, anger, joy, surprise, sadness) plus the neutral state.
- [**EmoDB**](https://www.kaggle.com/datasets/piyushagni5/berlin-database-of-emotional-speech-emodb) database is created by the Institute of Communication Science, Technical University, Berlin, Germany. Ten professional speakers (five males and five females) participated in data recording. The database contains a total of 535 utterances. The EMODB database comprises of seven emotions: 1) anger; 2) boredom; 3) anxiety; 4) happiness; 5) sadness; 6) disgust; and 7) neutral. The data was recorded at a 48-kHz sampling rate and then down-sampled to 16-kHz.
  
## Emotional Classification Performance
Given the current absence of standardized benchmarks and methods in speech emotion recognition, we conducted extensive evaluations across multiple test sets and performed a thorough comparison with recent state-of-the-art results. We used 6 datasets including RAVDESS, TESS, SAVEE, EMO-DB, CREMA-D, and EMOVO.


![](figure/comparions_graph.png?raw=true)
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
## Citation
```bibtex
@article{lee2025efficientser,
  author       = {HyeYoung Lee},
  title        = {Toward Efficient Speech Emotion Recognition via Spectral Learning and Attention},
  journal      = {arXiv preprint arXiv:2507.03251},
  year         = {2025},
  url          = {https://arxiv.org/abs/2507.03251}
}
