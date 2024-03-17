# **ANALYSIS**


## **Overview**
  The purpose of this project is to create an algorithm using machine learning that will predict if applicants will be successful with the money provided by Alphabet Soup.
  
## **Results**
## **Data Preprocessing**

   What variable(s) are the target(s) for your model? 
  
  - The target variable is "IS_SUCCESSFUL" which will indicate if the funding was successful or not.
  
   What variable(s) are the features for your model?

   - The feature variables are ""APPLICATION_TYPE", "AFFILIATION CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", and "ASK_AMT"
  
  What variable(s) should be removed from the input data because they are neither targets nor features? 

  - The variables "EIN" and "NAME" have been removed as they are not targets of features and these categorical 
      variables will not help the model. 

## **Compiling, Training, and Evaluating the Model**

  ## Number of neurons, layers and activation functions:
  
  - The first run had 2 hidden layers, with 10 and 5 neurons. Relu was used in both hidden layers, and sigmoid for the output and accuracy of 73%
  
 - The second run had 3 hidden layers, with 8,5 and 4 neurons. Tanh was used for all layers and the accuracy was still 73%
  
- The third run had 3 hidden layers, with 30, 15 and 25 neurons. Relu was used in the hidden layers and sigmoid for the output layer. This run had an accuracy of 73%
  
- The fourth run had 2 hidden layers, with  10 and 8 neurons. Tahn and relu were used for the hidden layers and relu for the output layer with an accuracy of 73%
  
 20 epochs was used in each case
  
  ## Were you able to achieve the target model performance? 
  
   - None of the models reached 75%
    
  ## Steps taken to increase performance:
  
   - Adjusting number of neurons and layers and changing activation functions. None results in any measurable or actionable change of performance.
  
  
## **Summary**

The model's accuracy remained at 73% over various configurations which could suggest that the choice of neural network architecture and activation functions has little impact on performance. Variations in the number of hidden layers and neurons did not significantly affect the model’s predictive ability and different activation functions (relu and tanh) in the hidden layers also had similar results. Future considerations could include further experimentation with hyperparameters such as learning rate, epoch number or batch size, or exploring alternative model architecture or learning methods.
