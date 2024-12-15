# Heart Disease Prediction

This project is my TP exam in machine learning and aims to predict the likelihood of heart disease using a dataset and various machine learning models. It involves preprocessing the data, training different classifiers, evaluating their performance using metrics like accuracy, precision, recall, and F1-score, and visualizing the results.

## Project Overview

### Features:

- Implements the following machine learning models:
  - Logistic Regression
  - Naive Bayes
  - Support Vector Machine (SVM)
  - Decision Tree
  - Random Forest

- Evaluates models using metrics from `sklearn.metrics`.

- Visualizes results with confusion matrices and an accuracy comparison histogram.

### Dataset:

The dataset used is `heart.csv`, which contains features related to heart disease prediction. Ensure the dataset is in the repository or provide the correct path to it.

### Clone the repository:

```bash
git clone https://github.com/Jlassi-Mohamed/heart-disease-prediction.git
```
Navigate to the project directory:

cd heart-disease-prediction

Usage

    Place the dataset heart.csv in the project directory or specify its path in the script.
    Run the script:

python analysis.py

Outputs include:

    Confusion matrix images for each model.
    A histogram comparing the accuracies of the models.

File Structure

heart-disease-prediction/
|— analysis.py # Main Python script
|— heart.csv # Dataset (ensure it’s in the directory or update the script path)
|— README.md # Project documentation
|— confusion_matrix_*.png # Confusion matrix images for each model
|— model_accuracies.png # Histogram comparing accuracies

Results

    The script identifies the best model based on accuracy and provides a detailed classification report.
    Confusion matrices for each model are saved as PNG files.
    A comparison histogram of model accuracies is saved as model_accuracies.png.

Dependencies

    Python 3.x
    pandas
    numpy
    matplotlib
    scikit-learn

Example Output

    Confusion Matrix: confusion_matrix_logistic_regression.png, etc.
    Accuracy Histogram: model_accuracies.png

Author

Jlassi Mohamed

Feel free to contribute by submitting issues or pull requests!
