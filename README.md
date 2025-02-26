# Airfoil Noise Prediction using PySpark

This project implements a machine learning pipeline to predict the sound level (in decibels) generated by airfoils based on various features using PySpark. The dataset used in this project is the NASA Airfoil Noise dataset and can be found at [Airfoil Self-Noise](https://archive.ics.uci.edu/dataset/291/airfoil+self+noise), it contains various aerodynamic and acoustic tests of airfoil blade sections. 

![Airfoil with flow](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-BD0231EN-Coursera/images/Airfoil_with_flow.png)

Diagram of an airfoil.

![Airfoil angle of attack](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-BD0231EN-Coursera/images/Airfoil_angle_of_attack.jpg)

Diagram showing the Angle of attack.

# Key Steps:
Key steps in this project include the following:
1. **Data Loading**: Load the NASA Airfoil Noise dataset.
2. **Data Cleaning**: Handle missing values and remove duplicates.
3. **Feature Engineering**: Combine features into a single vector and scale them.
4. **Model Training**: Train a Linear Regression model using the processed data.
5. **Model Evaluation**: Evaluate the model using Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2) metrics.
6. **Model Saving**: Save the trained model for future use.

This project was done as part of the [IBM Data Engineering specialization](https://www.coursera.org/professional-certificates/ibm-data-engineer) Feel free to implement this project on your own, Cheers!!!
