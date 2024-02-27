# Report on the Neural Network Model

## Overview of the analysis:
**  Nonprofit foundation Alphabet Soup want to select best applicants with best chance of success for their venture. By using ML and deep learning,I using their CSV file which has more than 34k organizations and tried to find successful applicants.


# Results:

## Data Preprocessing

**- The target variable for the model is 'IS_SUCCESSFUL'
**- The feature variable for the model are 'APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT '     

**- Removed variables from the input data because they are neither targets nor features is 'EIN' and 'NAME'.



## Compiling, Training, and Evaluating the Model

**-  selected neurons, layers, and activation functions for the neural network mode
         'used two hidden layers, where used 2 features are for first hidden layer and 1 feature
          for second hidden layer. For hidden layer used ReLU and for output used sigmoid
          activation function'
                
**- Achievement of the target model performance is 
                '268/268 - 0s - loss: 0.6053 - accuracy: 0.7314 - 178ms/epoch - 663us/step
                Loss: 0.6053096652030945, Accuracy: 0.7314285635948181'
**- Attempt to increase model performance
        ' To make model better I tried to change no of features in first and second hidden layers and added one more hidden layer too'
     
                

# Summary:
According to the evaluation above, the model was fairly successful with 73% of accuracy. Further testing would be required before determining if this model is ready to be applied for application decisions.

As the question of whether or not an applicant will be successful has binary output (Yes or No), it would be possible to apply a logistic regression model. Then, evaluation with a confusion matrix and classification report would provide additional information on the prediction ability of the model. 
Else, it would be possible to modify the model above by adjusting the number of hidden layers, as well as the activation functions or even the number of training epochs, it can become better model.
