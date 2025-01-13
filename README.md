# ICASSP-WIMAGA25
# Confidence Training for Ornamentation Detection

This repository provides the implementation for **Confidence Training for Ornamentation Detection**, as described in the associated paper: Confidence-Enhanced Models for Indian Art Music Analysis

## Abstract

Machine learning models for music have facilitated advancements in core applications like music pedagogy, singer identification, \textit{R\=aga} recognition, transcription, and genre classification. However, current systems lack prediction reliability measures, which are essential for applications like music pedagogy, where users could benefit from knowing the confidence of model outputs to better trust the predictions.
This work explores confidence estimation across two key tasks: ornamentation detection and \textit{R\=aga} classification. By adding a confidence head to existing models, we enable simultaneous output of predictions and confidence scores, trained using a novel target for confidence. We also address the data imbalance in targets by proposing a refined training methodology, resulting in improved model performance. The proposed methods outperform state of the art methods, such as confidNet and TCP target. Using the proposed models, we enhance the classification robustness by filtering out low-confidence test samples. This confidence-aware framework strengthens interpretability and applicability, supporting effective use in Indian Art Music analysis. 

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
