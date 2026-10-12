
# Rice Grain Classification Using Random Forest

## Project Overview

This project implements a **Random Forest classification model** using Python and Scikit-learn to distinguish between two rice varieties: **Cammeo and Osmancik**.

The project was completed as part of a Machine Learning lab assignment. The objective was to train a Random Forest classifier on the Rice (Cammeo and Osmancik) dataset and evaluate its performance using standard classification metrics.

## Objectives

- Implement a Random Forest classifier using Scikit-learn.
- Use morphological features of rice grains to predict their variety.
- Evaluate the model using a confusion matrix, accuracy, precision, sensitivity (recall), and F1 score.
- Practise supervised machine learning and model evaluation in Python.

## Dataset

The dataset was obtained from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/545/rice%2Bcammeo%2Band%2Bosmancik).

It contains 3,810 rice grain observations, each described by seven morphological features extracted from grain images.

The features include:

- `Area`
- `Perimeter`
- `Major_Axis_Length`
- `Minor_Axis_Length`
- `Eccentricity`
- `Convex_Area`
- `Extent`

The target variable is `Class`, which identifies each grain as either Cammeo or Osmancik.

## Methodology

The project follows a supervised machine learning workflow:

1. **Data preparation:** Load the dataset and separate the input features from the target variable.
2. **Train-test split:** Divide the data into training and testing sets.
3. **Model training:** Train a Random Forest classifier using Scikit-learn.
4. **Prediction:** Use the trained model to predict rice varieties in the test set.
5. **Evaluation:** Calculate the required classification metrics to assess model performance.

## Evaluation Metrics

The model is evaluated using the following metrics:

| Metric | Purpose |
|---|---|
| Confusion Matrix | Summarises correct and incorrect predictions for each class. |
| Accuracy | Measures the proportion of all predictions that are correct. |
| Precision | Measures how many positive predictions are correct. |
| Sensitivity (Recall) | Measures how many actual positive cases are correctly identified. |
| F1 Score | Combines precision and recall into a single metric. |

*Note:* Precision, sensitivity, and F1 score depend on which rice variety is designated as the positive class. The averaging method should be stated when reporting these metrics.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## How to Run the Project

1. Clone or download this repository.
2. Install the required Python libraries:

   ```bash
   pip install pandas numpy scikit-learn jupyter
   ```

3. Open the Jupyter Notebook containing the implementation.
4. Ensure the dataset is available at the file path specified in the code.
5. Run the notebook cells in order.
6. Review the confusion matrix, accuracy, precision, sensitivity, and F1 score printed by the program.

## Key Learning Outcomes

This project provided practical experience with:

- Building a supervised classification model.
- Applying the Random Forest algorithm.
- Preparing data for machine learning.
- Generating predictions using Scikit-learn.
- Evaluating classification performance using multiple metrics.

## Data Source and Reference

Cinar, I. and Koklu, M. (2019). *Classification of Rice Varieties Using Artificial Intelligence Methods*. International Journal of Intelligent Systems and Applications in Engineering.

Dataset: [UCI Machine Learning Repository — Rice (Cammeo and Osmancik)](https://doi.org/10.24432/C5MW4Z)

## Project Context

This repository documents a practical Machine Learning lab assignment focused on implementing and evaluating a Random Forest classifier. The results should be interpreted in the context of the dataset, the selected train-test split, and the model configuration used in the notebook.
