# Iris Flower Classification

This is a simple machine learning project that classifies iris flowers using the K-Nearest Neighbors (KNN) algorithm. The project is implemented in a Jupyter Notebook.

## Dataset

The dataset used in this project is the **Iris dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris):

- Download link: [https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data](https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data)

Make sure to save the file as `iris.data` or `iris.csv` in your project folder if you are loading it manually in the notebook.

## Files

- `IRIS_FLOWER_CLASSIFICATION.ipynb` – Jupyter Notebook containing the full code
- `.ipynb_checkpoints/` – Jupyter internal backups (can be ignored)

## Requirements

- Python 3  
- Jupyter Notebook  
- pandas  
- numpy  
- scikit-learn  
- matplotlib (optional)

Install dependencies:
```bash
pip install jupyter pandas numpy scikit-learn matplotlib
```
## How to Run

1. Download the dataset from the link above and place it in your project directory.
2. Start Jupyter:
```bash
jupyter notebeook
```
3. Open `IRIS_FLOWER_CLASSIFICATION.ipynb`.
4. Run all the cells step by step.

## What the Notebook Does

- Loads the Iris dataset from the `.data` file
- Converts it into a DataFrame with proper column names
- Splits the data into training and test sets
- Trains a K-Nearest Neighbors classifier
- Evaluates model accuracy

## Tutorial Source

This notebook was created by following this tutorial:  
[https://www.youtube.com/watch?v=rvCufeNddds](https://www.youtube.com/watch?v=rvCufeNddds)
