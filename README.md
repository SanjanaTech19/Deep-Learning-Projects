# Deep Learning Projects

A collection of practical deep learning projects for exploring machine learning workflows, neural networks, computer vision, and model evaluation.

The projects in this repository are designed to build understanding through complete, hands-on examples: preparing data, training models, evaluating results, and using models to make predictions.

## Projects

### Breast Cancer Classification

A neural network that classifies breast tumors as benign or malignant using the Wisconsin Diagnostic Breast Cancer dataset from scikit-learn.

The project demonstrates:

- Dataset loading and exploratory data analysis
- Feature and target separation
- Training and test data splitting
- Feature standardization
- Neural network construction with TensorFlow and Keras
- Training and validation metric visualization
- Test-set evaluation
- Sample prediction

See the project-specific documentation in [Breast-Cancer-Classification](Breast-Cancer-Classification/README.md).

## Technology Stack

### Currently Used

- **Python** for development and experimentation
- **Jupyter Notebook** for interactive analysis and documentation
- **NumPy** for numerical operations
- **pandas** for data loading and manipulation
- **Matplotlib** for visualizing data and training results
- **scikit-learn** for datasets, preprocessing, and data splitting
- **TensorFlow and Keras** for building and training neural networks

### Planned Tools

As the collection grows, projects may also use:

- **Seaborn** for statistical visualizations
- **OpenCV** and **Pillow** for image processing
- **PyTorch** for alternative deep learning implementations
- **scikit-learn metrics** for detailed classification reports and confusion matrices
- **TensorBoard** for experiment tracking and model monitoring
- **Streamlit** or **FastAPI** for model demos and simple deployment

The technology used by each project is documented in its own folder.

## Repository Structure

```text
Deep-Learning-Projects/
|-- Breast-Cancer-Classification/
|   |-- main.ipynb
|   |-- requirements.txt
|   |-- README.md
|   `-- .gitignore
`-- README.md
```

Datasets and other local files may be excluded from version control according to each project's `.gitignore` file.

## Getting Started

1. Clone or download this repository.
2. Open the project folder you want to explore.
3. Follow that project's README for installation and execution instructions.
4. Install the dependencies listed in the project's `requirements.txt` file.
5. Run the notebook cells from top to bottom.

For the current project:

```bash
cd Breast-Cancer-Classification
pip install -r requirements.txt
jupyter notebook
```

## Learning Goals

This project collection will focus on:

- Understanding the end-to-end machine learning workflow
- Comparing preprocessing methods and model architectures
- Measuring model performance with appropriate evaluation metrics
- Improving reproducibility through clear notebooks and dependency files
- Practicing responsible use of machine learning predictions
- Gradually moving from experiments to reusable applications

## Disclaimer

These projects are educational demonstrations. Model outputs should not be treated as professional medical, financial, or other high-stakes advice.
