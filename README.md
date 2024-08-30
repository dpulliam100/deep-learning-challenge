# deep-learning-challenge

Overview:
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special considerations for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively

Results: I was able to create a model with roughly 73% accuracy in predicting if an applicant is successful in their ventures or not.

Data Preprocessing:
  -What variable is the target of your model? The target variable in my model is "IS_SUCCESSFUL".
  
  -What variable are the features for your model? The features in my model included: "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", "ASK_AMT".
  
  -What variables should be removed from the input data because they are neither targets nor features? The variables removed from the data were "EIN" and "NAME" 

Compiling, Training, and Evaluating the Model?
  -How many neurons, layers, and activation functions did you select for your neural network model, and why?
  -Were you able to achieve the target model performance?
  -What steps did you take in your attempts to increase model performance?

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
