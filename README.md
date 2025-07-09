# Speech Emotion Recognition

### Introduction

🎙️ Speech Emotion Recognition (SER) using MFCCs and 1D-CNN with attention mechanisms.
🚀 Achieves state-of-the-art accuracy across six benchmark datasets (SAVEE, RAVDESS, TESS, etc.).
🧠 Robust, generalizable, and optimized for real-world human-computer interaction and assistive tech.
![](figure/archietecture.png?raw=true)
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
  
## Emotional Classification
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
