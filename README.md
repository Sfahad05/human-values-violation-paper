# Human Values Violation in App Reviews

This repository contains datasets and code for identifying and classifying human values violations in app reviews. The project focuses on developing machine learning models to detect these violations and categorize them effectively.

## Directory Structure

### Data Files
- **binaryclassificationdataset.csv**: Dataset for binary classification of human values violations.
- **newextendeddataset.csv**: Extended dataset for multiclass classification tasks.

### Documentation
- **Coding guideline for human values violation Dataset Annotation.pdf**: Detailed guidelines for annotating datasets for human values violation detection.

### Code Files

#### Binary Classification
- **`BIGRU_Binary_OVER_UNDER_Sampilng.ipynb`**: Implements Bidirectional GRU for binary classification with sampling techniques.
- **`BIRNN_Binary_OVER_UNDER_Sampilngv.ipynb`**: Implements Bidirectional RNN for binary classification.
- **`BiLSTM_Binary_OVER_UNDER_Sampilngv.ipynb`**: Uses BiLSTM architecture for binary classification tasks.
- **`CNN_Binary_OVER_UNDER_Sampilngv.ipynb`**: Employs a Convolutional Neural Network for binary classification.
- **`GRU_Binary_OVER_UNDER_Sampilng.ipynb`**: GRU-based model for binary classification.
- **`LSTM_Binary_OVER_UNDER_Sampilngv.ipynb`**: LSTM model implementation for binary classification.
- **`RNN_Binary_OVER_UNDER_Sampilng.ipynb`**: RNN-based model for binary classification.

#### Multiclass Classification
- **`GRU, BiGRU, CNN_multiclassification_for humanValues.ipynb`**: Implements GRU, BiGRU, and CNN for multiclass classification of human values violations.
- **`RNN_BiRNN_MultiClassification_for humanValues.ipynb`**: RNN and BiRNN-based models for multiclass classification tasks.

## Requirements
- Python 3.x
- Jupyter Notebook or JupyterLab
- Libraries: `pandas`, `numpy`, `scikit-learn`, `keras`, `tensorflow`

## Running the Experiments

### Binary Classification
1. Use **binaryclassificationdataset.csv** as the input dataset.
2. Choose a model notebook from the **Binary classification code** folder:
   - Examples: **`GRU_Binary_OVER_UNDER_Sampilng.ipynb`**, **`CNN_Binary_OVER_UNDER_Sampilngv.ipynb`**
3. Follow the instructions in the notebook to preprocess data, train the model, and evaluate results.

### Multiclass Classification
1. Use **newextendeddataset.csv** for multiclass classification experiments.
2. Select a notebook from the **Multiclassification code** folder:
   - Examples: **`GRU, BiGRU, CNN_multiclassification_for humanValues.ipynb`**
3. Execute the notebook to explore multiclass classification approaches and evaluate model performance.

## Data Annotation
For guidelines on annotating datasets for human values violations, refer to **Coding guideline for human values violation Dataset Annotation.pdf**.
