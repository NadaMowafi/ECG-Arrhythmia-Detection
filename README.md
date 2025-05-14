# Final Project - ECG Arrhythmia Detection

This project focuses on detecting and classifying cardiac arrhythmias using ECG signal analysis based on the **MIT-BIH Arrhythmia Database**. It involves a complete pipeline from signal preprocessing to machine learning-based classification.

## 🫀 Project Overview

Electrocardiograms (ECGs) are essential in identifying heart arrhythmias—irregularities in heartbeat rhythm. The project provides an end-to-end workflow to:

1. Explore and visualize ECG data
2. Preprocess raw signals
3. Extract meaningful features
4. Classify arrhythmias using machine learning models

## 🧰 Tools & Libraries

This project uses Python for implementation and the following libraries:

- [`wfdb`](https://pypi.org/project/wfdb/): Reading and handling MIT-BIH data
- `numpy`, `scipy`: Numerical computations and signal processing
- `matplotlib`, `pandas`: Data visualization and manipulation
- `scikit-learn`: Machine learning algorithms


## 📁 Project Structure 

ecg-arrhythmia-detection/
├── data/ # Raw and processed ECG data
├── notebooks/ # Jupyter notebooks for each analysis phase
├── docs/ # Documentation (project reports, API docs, references)
├── results/ # Output figures, reports, and logs 
├── requirements.txt # Python dependencies 
├── README.md # Project overview and instructions 

## 🔬 Project Phases

1. **Dataset Exploration and Visualization**  
   Visual inspection and understanding of ECG signals.

2. **Signal Preprocessing**  
   Filtering, normalization, and segmentation of raw ECG data.

3. **Feature Extraction**  
   Extracting time-domain, frequency-domain, or morphological features.

4. **Arrhythmia Detection and Classification**  
   Applying and evaluating machine learning models to classify arrhythmias.

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/ecg-arrhythmia-detection.git
cd ecg-arrhythmia-detection
