# BrainTumor

# Brain Tumor Detection Using MRI Images with CNN and Efficient Net B0

## Overview
This repository contains the implementation of a machine learning model for detecting brain tumors from MRI scans. The project utilizes a convolutional neural network (CNN) to classify MRI images into various categories indicating the presence of a tumor.

## Project Structure
- `brain_tumor_detection.ipynb`: The Jupyter notebook contains all the steps from data preprocessing to model evaluation.
- `predictions.py`: Use this script to load the trained model and make predictions on new MRI images.
- `brain.h5`: The saved model containing weights and the architecture.
- `LICENSE`: The license detailing the terms under which this project is shared.

## Getting Started

### Prerequisites
Before running this project, ensure you have the following installed:
- Python 3.6 or later
- TensorFlow 2.x
- NumPy
- OpenCV
- Matplotlib
- Jupyter Notebook

### Installation
Clone the repository and install the required dependencies:




### Installation
To set up your environment to run this code, follow the steps below:

```bash
git clone https://github.com/<your-github-username>/brain-tumor-detection.git
cd brain-tumor-detection
pip install -r requirements.txt
jupyter notebook brain_tumor_detection.ipynb
python predictions.py
```


