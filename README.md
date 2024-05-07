# Wine Quality Prediction

## Description

This dataset is related to red variants of the Portuguese "Vinho Verde" wine. It describes the amount of various chemicals present in wine and their effect on its quality. The dataset can be viewed as a classification or regression task. The classes are ordered and not balanced (e.g., there are much more normal wines than excellent or poor ones). Your task is to predict the quality of wine using the given data.

A simple yet challenging project, to anticipate the quality of wine. The complexity arises due to the fact that the dataset has fewer samples and is highly imbalanced. Can you overcome these obstacles and build a good predictive model to classify them?

### Input variables (based on physicochemical tests):
1. Fixed Acidity
2. Volatile Acidity
3. Citric Acid
4. Residual Sugar
5. Chlorides
6. Free Sulfur Dioxide
7. Total Sulfur Dioxide
8. Density
9. pH
10. Sulphates
11. Alcohol

### Output variable (based on sensory data):
12. Quality (score between 0 and 10)

## Acknowledgements

This dataset is also available from Kaggle & UCI Machine Learning Repository, [Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/wine+quality).

## Objective

1. Understand the Dataset & cleanup (if required).
2. Build classification models to predict the wine quality.
3. Fine-tune the hyperparameters & compare the evaluation metrics of various classification algorithms.

## Work Plan

1. **Data Exploration and Cleaning**:
   - Perform exploratory data analysis (EDA) to understand the distribution and relationships between different features.
   - Check for missing values and handle them appropriately.
   - Explore data imbalance and consider strategies for dealing with it.

2. **Feature Engineering**:
   - Extract meaningful features.
   - Scale the features if required.
   
3. **Model Building**:
   - Choose suitable classification algorithms.
   - Train the models on the training data.
   
4. **Model Evaluation**:
   - Evaluate the performance of models using appropriate evaluation metrics.
   - Fine-tune hyperparameters to improve model performance.
   
5. **Model Comparison**:
   - Compare the evaluation metrics of various classification algorithms to find the best-performing model.


## Usage

To run this project:
1. Clone this repository.
2. Install the required dependencies listed in the `requirements.txt` file.
3. Run the provided Jupyter Notebook or Python script to execute the project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
