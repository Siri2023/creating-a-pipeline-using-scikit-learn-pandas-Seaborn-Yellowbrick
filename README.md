# creating-a-pipeline-using-scikit-learn-pandas-Seaborn-Yellowbrick
## Introduction 
### Data
The breast cancer dataset used is one of the built-in datasets provided by scikit-learn.
### Steps
Import necessary libraries: importing the necessary libraries for the pipeline, including pandas, Seaborn, scikit-learn, and Yellowbrick.  

![image](https://user-images.githubusercontent.com/123089800/233320658-074084ab-a0dd-4ec8-98c6-c5818bf43a11.png)

Load and preprocess the data:loading the breast cancer dataset from scikit-learn and convert it to a pandas dataframe. then split the dataset into training and testing sets using the train_test_split function from scikit-learn.  
![image](https://user-images.githubusercontent.com/123089800/233321517-7f54442a-fbf0-4034-8654-cd609825cccf.png)

![image](https://user-images.githubusercontent.com/123089800/233321410-167edb52-d7e5-49d1-b30a-6871fbf1632c.png)  

![image](https://user-images.githubusercontent.com/123089800/233321622-def144f5-769e-41ee-bb13-30d082d6586e.png)  


Build a machine learning model: We initialize a logistic regression model using scikit-learn's LogisticRegression class and fit it on the training data using the fit method.  

![image](https://user-images.githubusercontent.com/123089800/233321758-28a349c5-2a28-4053-85ed-e56a3b390366.png)  

![image](https://user-images.githubusercontent.com/123089800/233321845-ff19906f-68ea-4718-a9df-1453ab202a53.png)  

![image](https://user-images.githubusercontent.com/123089800/233321982-efd9278f-1957-4124-83f5-c4a921d5bf87.png)  


Visualize model performance: We use Yellowbrick's ConfusionMatrix class to create a confusion matrix plot that visualizes how well the model performs on the testing data. We also use Yellowbrick's LearningCurve class to create a learning curve plot that visualizes the model's performance on the training data as we vary the size of the training set.  

![image](https://user-images.githubusercontent.com/123089800/233322143-2a84d3b2-9e02-4ce1-bcb9-a1838de11af2.png)  

![image](https://user-images.githubusercontent.com/123089800/233322247-2fb275ed-1fc5-478d-bb83-168479d1922f.png)  

![image](https://user-images.githubusercontent.com/123089800/233322775-338543aa-c6f6-4e04-87c2-46d23727f935.png)  

![image](https://user-images.githubusercontent.com/123089800/233322950-6e4743a2-637c-4980-94a1-48df80469f29.png)
