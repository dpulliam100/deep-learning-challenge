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
  -How many neurons, layers, and activation functions did you select for your neural network model, and why? My best performing model has 31 neurons, 4 layers, and uses "relu" activation. I did numerous trials, tested multiple layers, different numbers of neurons, and the way the neurons were structures (example: layer1 = 5, layer2 = 10, layer3 = 15 vs layer1 = 15, layer2 = 10, layer3 = 5).
  
  -Were you able to achieve the target model performance? The best performance I was able to achieve was .7319 accuracy, but after running the model for a second time with the same inputs the accuracy decreased for some unknown reason.
  
  -What steps did you take in your attempts to increase model performance? Changed the number of layers, epochs, neurons, structure of neurons.

Summary: 
The overall results of my model were mediocre. I would prefer to have had a higher accuracy rating. I probably could have worked on the structure of the dataframe, created more dummy variables, and possibly removed more of the data or categorized it differently. Structuring the original dataframe differently might have increased the accuracy rating but it is not known.
