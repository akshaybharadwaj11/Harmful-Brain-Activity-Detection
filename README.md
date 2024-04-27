# Harmful-Brain-Activity-Detection

This repository contains the source code for analyzing electroencephalography (EEG) data to detect various harmful brain activities, such as seizures, lateralized periodic discharges (LPD), and generalized rhythmic delta activity (GRDA). The aim of this project is to provide tools for researchers, clinicians, and healthcare professionals to better understand and diagnose neurological disorders using EEG signals.


## Overview

Electroencephalography (EEG) is a non-invasive method used to record electrical activity of the brain. It is widely used in clinical diagnosis of neurological disorders, including epilepsy and other condition that cause harmful brain activities. This project uses advanced signal processing techniques and machine learning algorithms to analyze EEG data and automatically detect different types of brain activities that are indicative of neurological disturbances.

## Installation

To set up a local development environment, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/your-username/harmful-brain-activity-analysis.git
cd harmful-brain-activity-analysis
```

2. Install required Python packages:It is recommended to use a virtual environment to manage dependencies.

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
```

## Usage

### Data
Consists of sample EEG and spectrogram data. The original dataset can be downloaded from [kaggle](https://www.kaggle.com/competitions/hms-harmful-brain-activity-classification/data)

### Preprocess
Code to perform data preprocessing such as noise filtering, and also contains feature extraction, converting EEG to spectrogram for training ResNet Model

### Model
Contains code to train ResNet50 model on single GPU and also perform distributed training on multiple GPUs using DDP(Distributed Data Parallel) and Model Parallel Techniques





