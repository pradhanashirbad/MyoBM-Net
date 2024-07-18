# MyoBM-Net

MyoBM-Net is a deep learning project that employs a convolutional neural network to extract features from a 6-channel wrist EMG using the GRABMyo dataset. A unique two-stage training strategy (S1 and S2) is explored in greater detail and results are provided. The dataset used is the GRABMyo data from 43 subjects collected over 3 different days. The extracted features are used for biometric matching to generate an authentication decision.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Acknowledgements](#acknowledgements)

## Introduction
MyoBM-Net leverages the power of convolutional neural networks to analyze electromyography (EMG) signals from the wrist. By extracting meaningful features from these signals, the network performs biometric matching, ultimately making authentication decisions.

## Dataset
The project utilizes the [GRABMyo dataset](https://physionet.org/content/grabmyo/1.1.0/), which includes EMG data from 43 subjects recorded over three different days. This dataset is publicly available and can be downloaded from the PhysioNet website.

## Installation
To install the required dependencies, run the following command:
pip install -r requirements.txt

## Usage
To run the experiments, execute the following command:
python run_S2.py
To view the results:
open reports_notebook/table_all_results.ipynb
open reports_notebook/plot_all_results.ipynb

## Acknowledgements
This is currently a reviewer's copy. More details of the work will be made publicly available



