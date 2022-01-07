# Organization Funding Deep Learning Model

**Overview**

​        The purpose of this analysis was to create a neural network deep-learning model to help determine whether applicants wanting to receive funding for their organization will be successful based on various criteria. The data used to create the model was based off of a csv containing applicant information from thousands of organizations including whether they ended up successful.

**Results**

-    Data Preprocessing:
  - The goal of the model was to determine whether or not an applicant was successful, so it was easily determined to use the variable titled “IS_SUCCESSFUL” as the target column to train the model. The target column contained 1’s and 0’s, 1 meaning it was successful, 0 meaning it was not successful.
  - The variable that  were considered to be features were: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT.
  -  The variables that that I considered to be neither targets nor features were the EIN and NAME columns.

- Compiling, Training, and Evaluating the Model
  - On the original model I had 2 hidden layers and an output layer. On the optimization file I added another layer mostly based from trial and error in order to determine what improved the model. I also played around the number of nodes until the model improved. 
  - I was not able to reach the target model performance but was however able to improve it.
  - I tried multiple different steps to improve the model. I had to reverse many of them due to making the target performance worse. Besides changing the number of layers and nodes, a few things I can mention which helped the performance was first to change the number of bins in the “CLASSIFICATION” column. I also looked at the “STATUS” feature and used only those in service and this also improved the model.

**Summary**

​        In summary, the results of the model were decent. I was not able to reach the target performance of 75% but I was able to make improvements to the original score of about 72.4% to about 73%. You could also use supervised machine learning models. An easy and straightforward model would be a simple logistic regression model.

 
