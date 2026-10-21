# Predictive Quality Control for Smart Manufacturing

## Module
**6FTC2175 – Advanced Machine Learning and Neural Network**

## Project Overview
This project investigates the use of machine learning and neural networks for predictive quality control in manufacturing. It compares classical machine learning approaches with neural network models to explore their predictive performance and suitability for industrial quality inspection.

The project is divided into three parts:

- **Part A – Classical Machine Learning:** A Random Forest classifier is developed for manufacturing defect prediction and compared with a Multilayer Perceptron (MLP).
- **Part B – Convolutional Neural Network:** CNN architectures are developed from scratch to classify casting product images into acceptable and defective categories.
- **Part C – Model Comparison:** The models are compared in terms of predictive performance, interpretability, computational requirements, training time, and potential deployment in manufacturing environments.

## Models Used

### Part A: Tabular Data
- Random Forest Classifier
- Multilayer Perceptron (MLP)

### Part B: Image Classification
- Baseline Convolutional Neural Network (CNN)
- Improved CNN architecture

## Datasets
The project uses two datasets:

1. **Manufacturing Defects Dataset** – used for tabular defect prediction.
2. **Casting Product Image Dataset** – used for image-based quality inspection.

Please refer to the notebook and the original dataset sources for the exact dataset details, labels, and preprocessing steps.

## Repository Contents

- `ANLNN_cw1.ipynb` – Jupyter/Google Colab notebook containing the implementation, experiments, evaluation, and visualisations.
- `report.pdf` – project report discussing the methodology, results, comparisons, and conclusions.
- `README.md` – project overview and repository documentation.
- `requirements.txt` – Python dependencies, if provided.

## Tools and Technologies
- Python
- Google Colab / Jupyter Notebook
- Pandas and NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib and Seaborn

## How to Run
1. Open `ANLNN_cw1.ipynb` in Google Colab or Jupyter Notebook.
2. Install the required dependencies if they are not already available.
3. Follow the notebook instructions to load the datasets and execute the code cells in order.
4. Review the evaluation metrics, confusion matrices, training curves, and model comparisons.

Dataset access or download steps may be required before running the notebook.

## Evaluation
The models are evaluated using appropriate classification metrics, including accuracy, precision, recall, F1-score, ROC-AUC, and PR-AUC where applicable. Training and validation curves are also examined for the CNN experiments.

The tabular and image-classification results represent different prediction tasks and should be interpreted separately.

## Limitations
Model performance depends on dataset quality, class distribution, preprocessing, and the selected train-test splits. Image classification results should also be checked for data leakage and duplicate images. Performance on these datasets may not directly generalise to real manufacturing environments.

## Academic Purpose
This repository was created for the **6FTC2175 Advanced Machine Learning and Neural Network** coursework. It documents the project's implementation and evaluation for academic purposes.
