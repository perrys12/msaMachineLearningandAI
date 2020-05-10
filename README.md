# msaMachineLearningandAI
Description: This project that I was interested in undertaking is through how machine learning and AI can be used in health. 
As a result, I particularly used Machine Learning in order predict the presence of Parkinson's disease in an individual.

Environmental Setup and Dependencies: The environmental setup and dependencies to use for this model to accurately predict the presence of Parkinson's disease is varied.
The most important environment setup is using numpy and pandas. NumPy is used for scientific computing throuhg using nubers while pandas is used for data manipulation. 

Step by Step Instruction: 
1. The first step to do is load in the dataset. 
2. We then move to exploring the data where I use df.shape and other commands to find any imbalances of data and to find any missing data 
3. I then start to scale the distribution of the dataset so it can be ready to be read and used for data manipulation.
4. We then start to build the machine learning model 
- We first get the features and labels from the Dataset. The features are all the columns except for the 'status', and the labels we used are within the label column 
- Initialised a MinMaxScaler and scale the features to between -1 and 1 to normalize them. The MinMaxScaler transforms features by scaling them to a given range. The fit_transform() method fits to the data and then transforms it. 
- Split the dataset into training and testing sets keeping 20% of the data for testing.
- Import the model that we are going to use which is called Random Forest. The model is Instantiated with 1000 decisions trees as we train the model for prediction 
- We use the forest's predict method on the test data to print and calculate absolute errors and its mean.
- We import mathplotlib to create a graph to highlight the prediction of Parkinson's in an individual from the dataset. 
- We use random forest to predict the exact number of prediction. 
