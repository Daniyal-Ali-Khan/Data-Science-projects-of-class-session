**Canada Per Capita Income Prediction**

**Overview**

This project aims to predict Canada's per capita income for the year 2020 using linear regression based on historical data from 1970 to 2016.

**Data**

The dataset used for this project is named Canada_per_capita_income.csv and contains two columns: year and income. The year column represents the years from 1970 to 2016, and the income column contains the per capita income values for each corresponding year.

**Methodology**

**Data Preprocessing:**
The dataset is loaded and inspected for any missing values or outliers. If required, data cleaning techniques such as imputation or removal of outliers are applied.

**Model Training:**
Linear regression model is trained on the historical data to learn the relationship between the year and the per capita income.

**Model Evaluation:**
The trained model's performance is evaluated using metrics such as mean squared error (MSE) or R-squared value to assess its accuracy in predicting per capita income.

**Prediction:**
Finally, the model is used to predict Canada's per capita income for the year 2020.

**Results**

The predicted per capita income for the year 2020 is ${{predicted_income_2020}}.


**Usage**

To run the prediction code:

Ensure you have Python installed on your system.

Install the required libraries by running pip install -r requirements.txt.

Execute the prediction script predict_income.py.

**Dependencies**

Python 

pandas

scikit-learn

matplotlib

Author

[Daniyal Ali Khan]

**License**

This project is licensed under the MIT License.

