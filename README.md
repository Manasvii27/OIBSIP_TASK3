# OIBSIP_TASK3
Sales Prediction Using Python

# Sales Prediction Using Python

Sales prediction involves forecasting the quantity of products or services that customers are likely to purchase based on various factors such as advertising expenditure, target audience, and advertising platform. In this project, we will explore sales prediction using machine learning with Python. We will use a dataset containing information about advertising spending on different platforms (TV, Radio, and Newspaper) and the corresponding sales figures.

## Steps to Implement Sales Prediction:

### Step 1: Import the Required Libraries

We start by importing the necessary libraries that will be used in this project. These include pandas, seaborn, numpy, plotly express, and matplotlib.

### Step 2: Load the Data into a DataFrame

The dataset is loaded into a pandas DataFrame, which allows us to perform data manipulation and analysis efficiently.

### Step 3: Data Exploration

In this step, we explore the data to gain insights into its structure and contents. We check the first few rows and last few rows of the DataFrame, examine the size and shape of the data, get information about data types and missing values, and generate descriptive statistics of the numerical columns.

### Step 4: Data Visualization

Data visualization helps us understand the relationships between different features and the target variable (Sales). We create a heatmap to visualize the correlation between features and use histograms and scatter plots to visualize the distributions and relationships between individual features and Sales.

### Step 5: Data Preprocessing

Data preprocessing involves converting data types and handling missing values, if any. In this step, we ensure that the data is in the appropriate format for model training.

### Step 6: Feature Selection and Data Splitting

Feature selection is a critical step in machine learning. We split the data into input features (X) and the target variable (y). We then further split the data into training and testing sets to evaluate the model's performance.

### Step 7: Model Training

We use a Linear Regression model to predict sales based on the advertising spending on TV, Radio, and Newspaper. The model is trained on the training data.

### Step 8: Model Evaluation

To assess the model's performance, we make predictions on the test data and calculate several evaluation metrics, including Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared value. These metrics help us understand how well the model's predictions align with the actual sales values.

## Conclusion

Sales prediction is an essential task for businesses to make informed decisions about advertising expenditure and expected sales. Through this Python project, we demonstrated how to use machine learning, specifically Linear Regression, to predict sales based on advertising spending on different platforms. The model's evaluation metrics provide insights into the model's accuracy and its potential impact on sales. By understanding the advertising impact, businesses can optimize their advertising strategies to achieve better sales results.
## Conclusion

In this project, we utilized Python and machine learning techniques, specifically Linear Regression, to perform sales prediction based on advertising spending on different platforms (TV, Radio, and Newspaper). The key findings and conclusions from the analysis are as follows:

1. Advertising Impact: The coefficients obtained from the Linear Regression model indicate the impact of each advertising medium on sales. TV and newspaper advertising have a positive impact on sales, while radio advertising has a slightly negative impact. This suggests that higher spending on TV and newspaper advertising can lead to increased sales, whereas more radio advertising might not yield the same positive results.

2. Model Performance: The model's evaluation metrics provide valuable insights into its accuracy and performance. The Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) indicate how close the model's predictions are to the actual sales values. The R-squared value represents the proportion of variation in sales that can be explained by the variation in advertising spending. In this case, the R-squared value of approximately 0.837 indicates that around 83.7% of the variation in sales can be explained by the advertising spending on TV, newspaper, and radio.

3. Data Preprocessing: Data preprocessing is a crucial step to ensure the data is in the appropriate format for model training. In this project, we handled data types and checked for missing values, ensuring that the data is clean and ready for analysis.

4. Visualization: Data visualization provided valuable insights into the relationships between advertising spending and sales. The heatmap helped us identify correlations between features, while histograms and scatter plots allowed us to understand the distributions and relationships between individual features and the target variable.

Overall, sales prediction using Python and machine learning offers a powerful tool for businesses to forecast future sales and make informed decisions. By continually analyzing and refining the models with updated data, businesses can stay competitive and adapt to changing market conditions effectively. With the insights gained from sales prediction, businesses can optimize their advertising strategies, manage resources efficiently, and ultimately drive revenue growth.
