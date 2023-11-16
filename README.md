# machine_learning_project-supervised-learning

## Project Overview
The aim of this project is to build a supervised learning model that effectively detects the presence of diabetes in patients based on pre-defined risk factors. The detailed model-building procedure can be found in the `Supervised Learning - Project.ipynb` file under the `Notebook` folder. The dataset used for this project is the "Diabetes" dataset originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The dataset is located in the `Data` folder in this repository.

### Project Description:

The project will involve the following tasks:

*	Exploratory data analysis and pre-processing: We will import and clean the data sets, analyze and visualize the relationships between the different variables, handle missing values and outliers, and perform feature engineering as needed.
*	Supervised learning: We will use the Diabetes dataset to build a machine learning model that can predict whether a patient has diabetes or not, using appropriate evaluation metrics such as accuracy, precision, recall, F1-score, and ROC-AUC. We will select at least two models, including one ensemble model, and compare their performance.

### Project Findings
* Overall, the risk  factors present in the dataset seem to have predictive values in determining if a patient has diabetes, as evidenced by the difference in average mean and distributions for those with and without positive outcome
* `Glucose`, `BMI`, and `Age` seem to be the most important risk factors for detecting diabetes as evidenced by the correlation map and feature importance scores
* Logistic, SVC, and Random Forest classifiers can be successfully used to predict the presence of diabetes in a given patient based on the identified risk factors
* Overall, Random Forest classifier showed the best and most balance performance in generalizing to new data.
