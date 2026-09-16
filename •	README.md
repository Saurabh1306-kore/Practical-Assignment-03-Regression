# Practical Assignment-03: Performance Evaluation of Regression Model

## 1. Project Title

**Performance Evaluation of Regression Model**

## 2. Application

**Median Income Prediction using Linear Regression**

## 3. Problem Statement

Develop a Regression Model for a real-world application and evaluate its performance using appropriate metrics. Additionally, implement Gradient Descent optimization for Linear Regression and analyze its performance.

## 4. Dataset

The **California Housing Dataset** was downloaded from Kaggle.

The dataset contains housing-related information such as:

- MedInc
- HouseAge
- AveRooms
- AveBedrms
- Population
- AveOccup
- Latitude
- Longitude

For this practical:

- **Input Feature:** AveRooms
- **Target:** MedInc

## 5. Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## 6. Methods Used

### Linear Regression

Linear Regression is used to predict the target value from the input feature.

### Gradient Descent

Gradient Descent is implemented manually to optimize the parameters of the Linear Regression model.

## 7. Performance Metrics

The models are evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## 8. Implementation

The implementation is performed in Google Colab.

The notebook includes:

1. Importing required libraries
2. Loading the Kaggle dataset
3. Checking the dataset
4. Checking missing values
5. Selecting input and target
6. Splitting the dataset into training and testing data
7. Implementing Linear Regression
8. Making predictions
9. Evaluating model performance
10. Plotting Actual vs Predicted values
11. Implementing Gradient Descent
12. Plotting Cost vs Epoch
13. Evaluating Gradient Descent performance
14. Comparing Linear Regression and Gradient Descent results

## 9. Results

The performance of the models is evaluated using MAE, MSE, RMSE and R² Score.

The Gradient Descent cost decreases with increasing epochs, showing that the model parameters are optimized during training.

## 10. Repository Contents

- `Practical_Assignment_03.ipynb` - Google Colab notebook
- `california_housing.csv` - Dataset
- `README.md` - Project information
- `screenshots/` - Output screenshots and graphs

## 11. Conclusion

Linear Regression was successfully implemented for median income prediction using the California Housing Dataset. The model was evaluated using different regression performance metrics. Gradient Descent was also implemented manually and its performance was analyzed using the cost function and evaluation metrics.

## 12. Author

**Saurabh Dharma Kore**

MIT Academy of Engineering, Alandi, Pune

Department: Electronics and Telecommunication Engineering
