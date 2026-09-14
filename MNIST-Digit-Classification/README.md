# MNIST Digit Classification

A deep learning project that trains a neural network to recognize handwritten digits from the MNIST dataset. The notebook demonstrates the core workflow for an image-classification problem, from loading and preprocessing image data to training, evaluating, and using the model for predictions.

## Project Structure

```text
MNIST-Digit-Classification/
|-- main.ipynb         # Data preparation, model training, evaluation, and predictions
|-- requirements.txt   # Python dependencies
|-- README.md           # Project documentation
`-- .gitignore         # Files excluded from version control
```

## Requirements

- Python 3.8 or later
- Jupyter Notebook or JupyterLab
- TensorFlow and Keras
- NumPy
- Matplotlib
- Seaborn
- OpenCV
- Pillow

Install the dependencies with:

```bash
pip install -r requirements.txt
```

## Run the Notebook

1. Open a terminal in this project directory.
2. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

3. Open `main.ipynb`.
4. Run the cells from top to bottom.

The notebook downloads or loads the MNIST handwritten-digit dataset, prepares the image data, trains a neural network, measures classification accuracy, and displays prediction results.

## Learning Goals

This project provides practice with:

- Image normalization and preprocessing
- Neural network architecture and training
- Classification accuracy and evaluation
- Visualizing handwritten digits and predictions
- Using TensorFlow and Keras in a Jupyter workflow

## Disclaimer

This project is an educational demonstration. Its results depend on the training configuration and should not be considered a production-ready digit-recognition service.