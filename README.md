# Carprice-Prediction-CarDhekho...
Predicting the car price using ML techiques with CarDehko Data
# Project Structure

This project has three major parts :

1.app.py - This contains Flask APIs that receives car details through GUI or API calls, computes the precited value based on our model and returns it.

2.random_forest_regression_model.pkl - module is used for serializing and de-serializing python object structures 

3.requirements.txt - This text file contains the packages needed to run the model 

4.Deployment - Heroko cloud platform used 
    
 # Following are the steps involved in buiding a stable model 
  
  1. Importing the data
  
  2. Data preprocessing 
  
  3. Handling the missing values if any 
  
  4. Going on with one-hot-encoding as their are categorical data 
  
  5. Finding the correlation and multicollinearity using pairplot and heatmap
   
      ![car pairplot](https://user-images.githubusercontent.com/70466481/91656915-4c2cdc80-eada-11ea-91c6-df8764608a94.png)
      
      ![car heatmap](https://user-images.githubusercontent.com/70466481/91656955-ca897e80-eada-11ea-940a-149e6ae635bb.png)
      
  6. Creating a train and test split of the data for training the model and again testing the model with useen data(test data)
  
  7. Moving on hyperparameter tunning with randomgrid cv.
       
  8. Searching the best parameters with 3 fold cross validation
  
  ![random search](https://user-images.githubusercontent.com/70466481/91657027-792dbf00-eadb-11ea-98e9-2a53cdb5f976.png)
  
  9. fit the model to train and test data and predict the results 
  
  10. Subtracting the predicted and given values and finding out the model accuracy 
 #Predicted-Given value o/p (Bell Curve)
 ![car prediction](https://user-images.githubusercontent.com/70466481/91657079-eb9e9f00-eadb-11ea-9766-f5609edca673.png)
 
 #Scatter plot
 ![car scatter](https://user-images.githubusercontent.com/70466481/91657080-eccfcc00-eadb-11ea-90fd-164f830517f2.png)

 
  
