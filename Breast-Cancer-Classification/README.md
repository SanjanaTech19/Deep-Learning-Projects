# Breast Cancer Classification

A beginner-friendly neural network project that classifies breast tumors as benign or malignant using the Wisconsin Diagnostic Breast Cancer dataset included in scikit-learn.

## Project Structure

```text
Breast-Cancer-Classification/
|-- main.ipynb         # Data preparation, training, evaluation, and prediction
|-- requirements.txt   # Python dependencies
|-- README.md           # Project documentation
|-- .gitignore          # Files excluded from version control
`-- data.csv            # Local dataset copy, excluded from Git
```

## Requirements

- Python 3.8 or later
- Jupyter Notebook or JupyterLab
- TensorFlow
- NumPy
- pandas
- Matplotlib
- scikit-learn

Install the dependencies with:

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow notebook
```

## Run the Notebook

1. Open a terminal in this project directory.
2. Start Jupyter:

   ```bash
   jupyter notebook
   ```

3. Open `main.ipynb`.
4. Run the cells from top to bottom.

The notebook loads the dataset, checks its structure and target distribution, splits the data into training and test sets, standardizes the features, trains the neural network, plots training and validation metrics, evaluates test accuracy, and runs a sample prediction.

## Model

The model is a Keras sequential network with:

- A flattening input layer for 30 standardized features
- A dense hidden layer with 20 ReLU units
- A two-unit sigmoid output layer
- Adam optimizer
- Sparse categorical cross-entropy loss
- 10 training epochs

The target labels are:

- `0`: Malignant
- `1`: Benign

The data is split with 80% used for training and 20% used for testing. Ten percent of the training data is used for validation during training.

## Dataset Note

The current notebook loads `sklearn.datasets.load_breast_cancer()` directly. The checked-in `data.csv` is not read by the notebook at present.

## Disclaimer

This project is for learning and demonstration purposes only. Its predictions must not be used for medical diagnosis or treatment decisions.
