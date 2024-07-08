# neural-network-challenge-2

## Background:

The following code is focused on creating a neural network that HR can use to predict whether employees are likely to leave the company. Additionally, HR believes that some employees may be better suited to other departments, so the model will predict the department that best fits each employee. These two columns should be predicted using a branched neural network.

The code will require functions, libraries, dependencies, import of a csv file, and Tensor Flow. 
This code is available at Github under (https://github.com/algjor/neural-network-challenge-2).

## Description of Code:
This code was completed using the following steps.

(1) - A repository was created called neural-network-challenge-2 in Git hub.

(2) - A starter code named attrition.ipynb was created on the local Git repository and pushed to GitHub.

(3) - The csv file spam-data.csv was imported for the data analysis from the url https://static.bc-edx.com/ai/ail-v-1-0/m19/lms/datasets/attrition.csv.

(4) - The file was then loaded onto Google Colab to work on the solution.

(5) - The data was pre-processed where the X_df data features were created with the y_df targets created.  A scalar was created with training and testing data encoded.

(6) - A model was created, compiled, and trained/fitted.  A branch was created for both the Department and Attrition targets.

(7) - The model was then evaluated with the testing data and the accuracy for both the Department and Attrition was predicted.

(8) - Key findings:

    1. Is accuracy the best metric to use on this data? Why or why not?
    Answer: Yes - It shows the accuracy for each prediction individually.
    
    
    2. What activation functions did you choose for your output layers, and why?
    Answer: Softmax for Department due to multi-classification and Sigmoid for Attrition due to binary-classification


    3. Can you name a few ways that this model might be improved?
    Answer: Use Categorical_Crossentropy for Department due to multiple outcomes/categories and continue to use Binary Crossentropy for Attrition due to yes/no outcome. 
    
