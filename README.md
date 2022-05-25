# Neural_Network_Charity_Analysis

**Overview of the analysis:**

Here I used Neural Networks to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

**Results:**

Using bulleted lists and images to support your answers, address the following questions.

**Data Preprocessing**

*What variable(s) are considered the target(s) for your model?*

For this we looked at application type and class, and if they were successful or not.

*What variable(s) are considered to be the features for your model?*

![image](https://user-images.githubusercontent.com/94264746/170380956-43cef081-55d4-4d97-aa31-1654ba5991fc.png)

Per the image, we looked at Application Type, Affiliation, Classification, Use Case, Organization, Income Amt, and Special Considerations.

*What variable(s) are neither targets nor features, and should be removed from the input data?*

![image](https://user-images.githubusercontent.com/94264746/170381331-4443aa21-fb2f-4a9e-9f6d-d572a72c424c.png)

For this we dropped EIN and Name.

**Compiling, Training, and Evaluating the Model**

*How many neurons, layers, and activation functions did you select for your neural network model, and why?*

![image](https://user-images.githubusercontent.com/94264746/170381806-faded7c5-824a-4c3f-8617-c3e0823c2ff7.png)

I went with 2 neurons, 3 layers, and 1 Activation function.

*Were you able to achieve the target model performance?*

![image](https://user-images.githubusercontent.com/94264746/170381870-6f892abb-acb7-473e-b5df-ba5e1b04899c.png)

Not quite, with a loss of 0.56, and accuracy of about 73%.

*What steps did you take to try and increase model performance?*

![image](https://user-images.githubusercontent.com/94264746/170382475-aa69f132-f2d4-43c8-9f12-94ccbb3a3db9.png)

I redid the Neural Network, added a few more neurons and another layer in order to increase the efficiency.

**Summary:**

![image](https://user-images.githubusercontent.com/94264746/170382583-838aa8c7-1a7a-450d-b297-f1dcc513b523.png)

The second Neural Network was better, with a loss of about 44% and accuracy of 79%.

![image](https://user-images.githubusercontent.com/94264746/170382691-6e29698e-664d-4b37-9244-3c8e75949fa6.png)

The Random Forest Classifier overall worked to categorize the data. I would recommend cleaning the data a bit more in order to get a higher accuracy, possibly by seperating each charity by type.
