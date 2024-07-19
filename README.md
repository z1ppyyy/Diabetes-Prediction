# Diabetes Prediction Using Machine Learning
Diabetes Prediction using Machine Learning

## Project Overview

This project aims to predict diabetes using a machine learning model, specifically a Random Forest Classifier. The model is trained on a dataset containing various health-related features of individuals, and it predicts whether an individual has diabetes.

## Dataset

The dataset used in this project contains the following features:
- `gender`: Gender of the individual (categorical)
- `age`: Age of the individual (numerical)
- `hypertension`: Presence of hypertension (binary)
- `heart_disease`: Presence of heart disease (binary)
- `smoking_history`: Smoking history of the individual (categorical)
- `bmi`: Body Mass Index (numerical)
- `HbA1c_level`: HbA1c level (numerical)
- `blood_glucose_level`: Blood glucose level (numerical)
- `diabetes`: Target variable indicating the presence of diabetes (binary)

## Project Structure

The project includes the following steps:
1. **Data Preprocessing**
   - Load the dataset.
   - Encode categorical variables.
   - Split the dataset into training and test sets.

2. **Model Training**
   - Train a Random Forest Classifier on the training set.

3. **Model Evaluation**
   - Evaluate the model using confusion matrix, accuracy score, and cross-validation.

4. **Model Visualization**
   - Visualize the model's performance using confusion matrix, ROC curve, feature importances, learning curve, and precision-recall curve.

## Installation

To run this project, you'll need Python and the following libraries:
- numpy
- pandas
- scikit-learn
- seaborn
- matplotlib

You can install the required libraries using pip:

```bash
 pip3 install -r requirements.txt
```

## Set up

Clone the Repository
```
git clone git@github.com:z1ppyyy/Diabetes-Prediction.git
```

## Contributing

Contributions are welcome! Please create a pull request or submit an issue if you have any suggestions or improvements.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
