# ML-Project
GitHub repo: Predict admission chances using ML.

# Admission Chances ML Predictor

![Admission Chances ML Predictor](https://github.com/YBIFoundation/Dataset/raw/main/Admission%20Chance.csv)

**Description:**
This GitHub repository hosts a machine learning project that predicts admission chances for aspiring students. It offers valuable insights into admission likelihoods, benefiting both students and universities.

**Project Overview:**
The project comprises several stages with distinct objectives.

### Data Preparation

In this phase, the code:

- Imports libraries (e.g., pandas, numpy, matplotlib, seaborn) for data manipulation and visualization.
- Fetches the admission chance dataset from a URL and stores it in a pandas DataFrame.
- Defines the target variable (admission chance) and features.
- Splits the data into training and testing sets for model development and evaluation.

### Model Selection

Focused on building a predictive model, this stage involves:

- Importing essential libraries, like sklearn's train_test_split and DecisionTreeRegressor.
- Opting for a Decision Tree Regressor with a max depth of 3 for model construction, ensuring reproducibility with a random state.
- Training the model on the training dataset.
- Assessing the model's performance on both the training and testing datasets.
- Conducting cross-validation to evaluate the model's robustness.

### Model Validation

Here, the code delves into hyperparameter tuning and validation:

- Retrieves the model's hyperparameters.
- Establishes a pipeline encompassing the Decision Tree Regressor model.
- Executes a grid search to pinpoint the best hyperparameters, using cross-validation.
- Identifies the best estimator with optimal hyperparameters.
- Fits the best estimator on the training data.
- Generates predictions using the best estimator and computes various regression metrics (mean absolute error, mean absolute percentage error, and R-squared).

### Model Visualization

Additionally, the code provides a visual representation of the Decision Tree Regressor model. It employs Matplotlib to plot the tree, simplifying comprehension of the model's decision-making process.

### Save Model

Lastly, the code facilitates saving and loading the trained model via the pickle library. This feature allows users to retain the best-performing model for future use or deployment in production applications.

This GitHub repository proves valuable for those interested in predicting admission chances based on academic credentials. The code can be adapted and extended for similar machine learning projects in education and admissions. Feel free to explore and customize the code to enhance your understanding of admission chances or streamline your institution's admission procedures.
