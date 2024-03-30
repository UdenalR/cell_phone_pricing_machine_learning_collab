Objective of the Code:
This code aims to perform exploratory analysis and create three machine learning models to predict price ranges of mobile devices based on various features and also explores the importance of these features in logistic regression, decision tree, and random forest models.

Why choose those models?
Logistic Regression:

Applicability: Since the task involves predicting price ranges (which can be converted into binary classes), logistic regression is suitable.

Interpretability: Logistic regression provides interpretable results, making it easier to observe the impact of each feature on the price range.

Efficiency: Logistic regression can handle large datasets well, making it good for initial modeling.

Decision Tree:

Non-Linearity: Decision trees can capture non-linear relationships between features and target variables which is good since mobile device prices can be influenced by various non-linear factors.

Feature Importance: Decision trees provide feature importance scores that can help us identify which features are most relevant for predicting price ranges.

Interpretability: Although decision trees can be complex, they also can offer a visual representation of decision-making processes that can help us understand how the model makes the predictions.

Random Forest:

Ensemble Method: Random forest is a method that combines multiple decision trees that offer generalization and reduce overfitting.

Robustness: Random forest models are robust against noise and outliers which can help us deal with that type of data.

Overall Justification:

Diversity With those 3 models we can cover a range of techniques from linear to non-linear and ensemble methods.

Comparison: Using multiple models allows us to compare their performance metrics (e.g., accuracy, precision, recall) and choose the most effective model for predicting price ranges accurately.

Robustness: With 3 models we can increase the robustness of our analysis, ensuring a more precise predictive capability.

Explanation Outline:
Importing Libraries:
Pandas: Data manipulation in DataFrame format. Matplotlib and Seaborn: Data visualization in graphs. Scikit-learn: Tools for data preprocessing and machine learning model creation.

Loading and Preprocessing Data:
Loads data from the 'train.csv' file into a DataFrame. Renames columns to English for better understanding. Creates new columns from existing ones for further analysis.

Exploratory Analysis and Visualizations:
Bar Plots: Analyzes the relationship between battery capacity, RAM, and device prices. Scatter Plots: Explores the relationship between RAM and price, as well as other features with price ranges. Count Plot: Counts the number of devices in each price range. Heatmap: Shows the correlation between all variables in the dataset.

Machine Learning Model Creation:
Divide the data into training and testing sets. Handles infinite and very large values in the data. Uses an imputer to deal with missing values. Creates and trains Logistic Regression, Decision Tree, and Random Forest models. Makes predictions and evaluates model accuracy. Shows feature importance in each model through bar charts. Insights and Motivations: Exploratory Analysis: Helps understand the relationship between different features and the price range of mobile devices. Visualizations: Facilitate the understanding of exploratory analysis through intuitive graphs. Machine Learning Modeling: Aims to create accurate models to predict price ranges based on available features. Feature Importance: Identifies which variables have the most influence on model predictions.
