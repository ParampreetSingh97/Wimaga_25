# Confidence Training for Ornamentation Detection

This repository provides the implementation for **Confidence Training for Ornamentation Detection**, as described in the associated paper: Confidence-Enhanced Models for Indian Art Music Analysis

## Overview

This project focuses on training a model for ornamentation detection in audio signals with confidence estimation. The confidence model helps to predict the reliability of the classification for each time frame.

## Dependencies

The following libraries are required to run the code:

- **Numpy**
- **TensorFlow/Keras**
- **Scikit-learn**
- **Matplotlib**
- **Pandas**
- **TQDM**
- **Action Seg Models**

## File Structure

- `confidence_training_ornamentation.ipynb`: Main Jupyter Notebook for training and evaluation.
- Additional utility scripts and modules may be imported for custom layers, loss functions, and data preprocessing.

## Setup Instructions

1. Clone the repository:

   ```bash
   git clone <repository-link>
   cd <repository-directory>
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook confidence_training_ornamentation.ipynb
   ```

## Usage

1. Preprocess your dataset to fit the required input shape.
2. Customize model parameters as needed within the notebook.
3. Train the model using the provided cells.
4. Evaluate the results and analyze confidence predictions.

## Citation

If you use this code in your research, please cite the associated paper: Kumar, S., Singh, P., & Arora, V. *Confidence-Enhanced Models for Indian Art Music Analysis,* in ICASSP Sattelite Workshop on Indian Music Analysis and Generative Applications (WIMAGA), 2025.
