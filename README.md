# diabetes-predictors
## Project 4: 

## Project objective
What are the primary factors that can predict the onset of diabetes? The Kaggle dataset below collected records from multiple healthcare providers that include gender, age, smoking history, and more.

## Code
- Initial_Spark_Cleanup .ipynb
    - Imports and cleans original dataset

- Diabetes Model Accuracy and visualisation.ipynb
    - Contains initial summary charts as well as some additional machine learning model and progression model

- diabetes_tensorflow.ipynb
    - Contains code for tensorflow model used in presentation. Run in Google Colab.

- logistic_regression_diabetes_model_Oversampling_added.ipynb
    - Contains code for standard logistic regression model and oversampling logistic regression model. 

- Visualizations Folder
    - Contains images used in presentation.

## Results 
![Screenshot 2023-06-08 at 9 56 58 PM](https://github.com/sewiteskinder/diabetes-predictors/assets/114887398/68d86cd5-7c04-4388-8cd6-21293ad988ff)


Results suggest Oversampling Model is accurate for predicting "diabetics" and the Logistic Regression model is more accurate at predicting "non diabetics". We would recommend using the Oversampling model overall because of the balance accuracy of 0.85 compared to the Logistic and TensorFlow at 0.82 and 0.85, respectively. This is because the oversampling compensates for the minority group in the dataset.

## Team members: 
Sewit Eskinder, Eduardo Peris, Arunkumar Sridharan, Daniela Castellon, Kudirat Abdulsalam

## References

### Link to data: 
https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset
### Link to presentation: 
https://docs.google.com/presentation/d/1vAhGA7Tj5wZ1kiI6tgH5uPNxHS3bTpOMqj96hUplu3A/edit?usp=sharing

### CSV Files: 

Original uncleaned data: diabetes_prediction_dataset.csv

Cleaned data: Diabetes_Prediction_Clean.csv 
- This files contains primary summary data for main dataset as well as some exploratory machine learning model work. 


