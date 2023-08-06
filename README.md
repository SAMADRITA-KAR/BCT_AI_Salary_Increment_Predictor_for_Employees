# BCT_AI_Salary_Increment_Predictor_for_Employees
# Salary Increment Predictor

This is a simple Salary Increment Predictor project that uses Linear Regression to predict salary increments based on years of experience. The model is trained on a dataset containing information about employees' years of experience and their corresponding salaries.

## Dataset

The dataset used for this project is stored in a CSV file named `Salary_Data.csv`. It contains two columns: `YearsExperience` and `Salary`. If there are any missing values in the `Salary` column, they are filled with the average salary of the available data.

## Getting Started

To run the project, follow these steps:

1. Clone the repository to your local machine.
2. Ensure you have Python and the required libraries installed (NumPy, pandas, matplotlib, seaborn, scikit-learn).
3. Run the `salary_increment_predictor.py` script to train the model and make salary predictions.

## Running the Code

In the `salary_increment_predictor.py` script, the following steps are performed:

1. Data loading and preprocessing: The dataset is loaded using Pandas, and missing values in the `Salary` column are handled by filling them with the average salary.
2. Data splitting: The data is split into training and testing sets for model evaluation using scikit-learn's `train_test_split` function.
3. Model training: A Linear Regression model is trained using the training data.
4. Making predictions: The model is used to predict salary increments for a given number of years of experience.
5. Plotting: A scatter plot of the training data and the regression line is generated to visualize the relationship between years of experience and salary.

## Results

After running the code, you will see the predicted salary increment for an input value of 2.5 years of experience. Additionally, a plot will be displayed showing the data points and the regression line representing the salary increment based on years of experience.

Feel free to modify the `salary_increment_predictor.py` script or use your own dataset to further explore and experiment with the model.

## License

# This project is authored by [Samadrita_kar].

