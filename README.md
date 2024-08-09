 <h3>Project Overview :</h3> 

In this project, titled "Big Sales Prediction," I aimed to predict sales figures using a machine learning model. 
The dataset was imported from GitHub, provided by the YBI Foundation. To accomplish this, I used the Random Forest Regressor,
a robust machine learning algorithm known for its ability to handle both linear and non-linear data efficiently.

<h3>Data Preprocessing:</h3>
The first step involved importing the necessary libraries for data manipulation, analysis, and visualization.
After loading the dataset, I performed initial exploration and basic functions to understand the data structure.

During preprocessing, I encountered missing values in the "Item_Weight" column, with 2,389 null entries.
These missing values were imputed using the mean of the column to maintain data consistency. Additionally, 
I converted all categorical variables to numerical format using replace function, assigning categories to numerical values ranging from 0 to 9. 
This step was essential to ensure the machine learning model could process the data.

<h3>Feature Selection and Model Building:</h3>
Next, I defined the target variable, which is the sales figure to be predicted, and selected the relevant feature
variables that influence sales. I imported the machine learning library and used the Random Forest Regressor to build the model. 
Before training the model, I standardized the feature variables to bring them to a common scale, which enhances model performance.

The dataset was then split into training and testing sets to evaluate the model’s performance. The training set was used to train the model,
and the testing set was used to validate its predictions.

<h3>Model Evaluation and Visualization:</h3>
After building the model, I made predictions on the test data. To assess the accuracy and performance of the model,
I used appropriate metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared value.

Finally, I visualized the actual vs. predicted values to understand the model’s predictive capabilities better. 
The visualization highlighted how well the model could predict sales figures, providing a visual insight into its accuracy.
