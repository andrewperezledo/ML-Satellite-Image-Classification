# Project 2

## Description
This project involves training machine learning models on a dataset to perform classification tasks. It includes preprocessing of data, dimensionality reduction, model training, hyperparameter tuning, and evaluation. The primary focus is on SVM and Random Forest classifiers as stated per the requirements of this course project. However, it would be ideal to perform this task with convoluted neural networks.

## Getting Started

### Dependencies
- Python 3
- Libraries: numpy, pandas, matplotlib, scikit-learn, seaborn, scipy, time, pickle

### Installing
- Ensure Python 3 is installed.
- Install required libraries using pip:
- Alternatively, you can also download the Anaconda package and use JupyterNotebooks

### Executing Program
1. Load your dataset. Replace the lines like `ships_dataset/ship_data.npy` with your dataset paths.
   ```
   X = np.load('your_dataset/data.npy')
   t = np.load('your_dataset/labels.npy')
   ```
2. Run the entire notebook to preprocess data, train models, and evaluate results. This was ran on UF's HiPerGator supercomputer, so beware of slower training times and dangerous conditions when ran on local devices.


## Modifying the Code
- To use a different test set, update the dataset loading section with the path to your new dataset.
- Modify hyperparameters in each section as to find the best result for your dataset, especially in the GridSearchCV param_grids.


## Author
Andrew Perez-Ledo

