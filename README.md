# COM7019 – Assignment  
## MNIST Image Classification using Neural Networks

This repository contains the complete Python implementation for **Task 1** of the COM7019 Artificial Intelligence and Neural Networks module.

The project builds a deep neural network from scratch (using NumPy) to classify handwritten digits from the MNIST dataset and compares the performance of **Sigmoid** and **Tanh** activation functions.

---

## Repository contents

- `Assignment.ipynb`  
  Jupyter Notebook containing the full implementation, training, evaluation, and visualisation code.

- `npy.zip`  
  Zipped MNIST dataset files used by the notebook:
  - `train_images.npy`
  - `train_labels.npy`
  - `test_images.npy`
  - `test_labels.npy`

- `README.md`  
  Instructions for running the notebook and understanding the repository structure.

---

## How to run the notebook

1. Clone or download this repository.
2. Extract `npy.zip` into the same directory as `Assignment.ipynb`.
   After extraction, the following files must be present in the folder:
   - `train_images.npy`
   - `train_labels.npy`
   - `test_images.npy`
   - `test_labels.npy`
3. Open `Assignment.ipynb` in Jupyter Notebook or JupyterLab.
4. Run all cells from top to bottom to reproduce the results shown in the report.

---

## What the notebook does

- Loads and preprocesses MNIST digit images (28×28 grayscale).
- Builds a neural network with:
  - 1 input layer
  - 6 hidden layers
  - 1 output layer with 10 neurons
- Trains and evaluates the model twice:
  - Once using **Sigmoid** activation in the hidden layers
  - Once using **Tanh** activation in the hidden layers
- Uses **Softmax** in the output layer to generate class probabilities.
- Produces accuracy metrics, training curves, confusion matrices, and sample predictions used as evidence in the report.

---

## Notes

The MNIST dataset files are provided in a compressed `.zip` file due to GitHub file size limitations.  
This does not affect reproducibility, as the notebook directly loads the extracted `.npy` files.

All results shown in the accompanying report can be reproduced by following the steps above.

