# House Price PRediction
The project on House Price Prediction for Surprise Housing, a US-based company entering the Australian market, involves building a regression model to predict the actual value of prospective properties. This model is crucial for the company's strategy to purchase houses at a price below their actual values and sell them at a higher price. The dataset provided contains information on the sale of houses in Australia, which will be used to train the model.


## General Information
### Background:
The primary goal is to model the price of houses with the available independent variables to assist the management in understanding how prices vary with these variables. This understanding will enable the company to strategize effectively and focus on areas that promise high returns. Additionally, the model serves as a valuable tool for grasping the pricing dynamics in the Australian market, aiding the company in making informed investment decisions.

### Business Problem:
The primary business problem addressed by this project is to building a regression model to predict the actual value of prospective properties.

### Key Findings:
Significant Variables: The analysis of the Lasso model revealed that the material of the roof (e.g., RoofMatl_Membran, RoofMatl_WdShngl) are among the most significant variables in predicting the price of a house. This insight suggests that certain features, particularly those related to the construction and material quality of the house, play a crucial role in determining its value.

Model Performance: The model's performance was evaluated using cross-validation and a test set. The mean cross-validation Root Mean Squared Error (RMSE) was approximately $49,282, indicating the average deviation of the model's predictions from the actual house prices during the cross-validation process. On the unseen test set, the model achieved an RMSE of $50,799.61 and an R-squared value of 0.66, suggesting that the model explains about 66% of the variance in house prices.


## Conclusions

The regression model developed for Surprise Housing provides valuable insights into the factors influencing house prices in Australia. By identifying significant variables and optimizing the model's parameters, the company can make strategic decisions to maximize its returns in the new market. Continuous refinement and validation of the model are essential to adapt to changing market conditions and maintain its predictive accuracy.

## Steps that I followed for model building:
Load and Prepare the Data:
Load the dataset from 'train.csv'.
Perform initial data exploration to understand the structure and content of the data.
Clean the data by handling missing values, removing duplicates, and addressing any data redundancies.

Feature Engineering:
Create dummy variables for categorical features.
Derive new metrics if applicable, based on the existing data, that could be useful for the model.
Data Splitting:

Split the dataset into training and testing sets to evaluate the model's performance on unseen data.

Model Building:
Choose a regression model. Linear Regression is a common starting point for regression tasks.
Train the model on the training set.

Model Evaluation:
Predict the target variable (property values) for the test set.
Evaluate the model's performance using appropriate metrics, such as Mean Squared Error (MSE) and R-squared (R2).

Addressing High Correlation:
Review the highly correlated features identified earlier and decide on actions to take, such as removing one of the features from each highly correlated pair or combining them into a new feature.

## Technologies Used
- **Pandas - 1.0:**
  - Pandas was employed for efficient data manipulation and analysis, providing a powerful toolset for handling the loan dataset.

- **NumPy - 1.0:**
  - NumPy played a pivotal role in performing numerical operations and array manipulations, contributing to the core functionality of data processing.

- **Seaborn - 2.0:**
  - Seaborn, a statistical data visualization library, was utilized for creating insightful visualizations, aiding in the exploration of patterns and relationships within the data.

- **Matplotlib - 3.0:**
  - Matplotlib complemented Seaborn by offering additional customization and flexibility in crafting visual representations of the analysis results.

- **Scikit-learn - 4.0:**
  - Scikit-learn provided machine learning utilities for potential model development and predictive analytics, though the focus of this project was primarily on exploratory data analysis.

- **Jupyter Notebooks - 5.0:**
  - Jupyter Notebooks served as the primary platform for code development, facilitating an interactive and iterative workflow conducive to data exploration and analysis.

These technologies collectively formed a robust toolkit for the execution of the Lending Club case study, enabling efficient data manipulation, exploration, and visualization to derive meaningful insights from the loan dataset.

## Acknowledgements
This project stands on the shoulders of various sources and inspirations, and I extend my gratitude to:


Online Tutorials and Documentation:
Various online tutorials and documentation resources have been instrumental in enhancing my understanding of data analysis techniques, data cleaning procedures, and exploratory data analysis.
References:
Upgrad
Module3: Exploratory Data Analysis
Module 4: Introduction to Git and GitHub
Course 4 &5 : Machine learning

## Contact
Created by: Amit Ranjan [@AmitwaytoDS] https://github.com/AmitwaytoDS/Advance_Regression_House_Price_Prediction - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
