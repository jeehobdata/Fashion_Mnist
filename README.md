# INDEPENDET STUDY
This is an Independent Study to run supervised machine learning on fashion MNIST data. It proceeded under the supervision of Prof. Andrew Catlin, Program Director of Data Analytics and Visualization at the Katz School, Yeshiva University.


This independent study(IS) aims to learn supervised machine learning using Scikit-learn and comparing the accuracy score of the results with the results of running a model by DataRobot, an auto machine learning(AutoML) tool. For the dataset, Fashion MNIST and MNIST datasets are used.

This IS starts with learning supervised machine learning by using Scikit-learn as a machine learning tool.

[Sources]
- Datacamp: Supervised Learning with scikit-learn (https://www.datacamp.com/courses/supervised-learning-with-scikit-learn)
- Hands on Machine Learning with Scikit-Learn & TensorFlow (https://github.com/ageron/handson-ml)

[Datasets]
- Fashion_MNIST (https://www.kaggle.com/zalando-research/fashionmnist)
- MNIST (http://yann.lecun.com/exdb/mnist/)

[Tools]
- Scikit-Learn(https://scikit-learn.org/stable/) 
- Google Colab(https://colab.research.google.com/notebooks/welcome.ipynb)
- Data Robot(https://www.datarobot.com/)


## Steps
1. For the beginning, I run a classification model on MNIST data  (https://github.com/jeehobdata/Fashion_Mnist/blob/master/Recognizing%20hand-written%20digits%20by%20Scikit-learn.ipynb)

2. Secondly, run the classification model used on the previous dataset on Fashion MNIST data (Used Google Colab)  
(https://github.com/jeehobdata/Fashion_Mnist/blob/master/tensorflow2beachhead.ipynb)

3.Run DataRobot 
- To run The DataRobot, the test set of the Fashion MNIST data is used, and 14 models were identified.
- As the result, Light Gradient Boosted Trees Classifier with Early Stopping (SoftMax Loss) (16 leaves) shows recommended for deployment with 87.09% accuracy, while AVG Blender shows the highest accuracy score as 87.14%. TensorFlow Neural Network Classifier also had a high accuracy score as 85.59% 

## Key Takeaways
1. Classification Model Accuracy Validation
  - Accuracy score and hamming Loss are a way to measure the accuracy of classification models. 
  - In Scikit-learn, the ROC_AUC method does not support classification mode. 
 
2. DataRobot, other Auto AI saves lots of time
  - Based on the uploaded dataset, DataRobot detects and applies a number of available Machine Learning models for the given datasets at the same time. By that approach, the users can see results of each model without running the models one by one, so that the users could choose the most appropriate model among the list by simply comparing them.

3. Never underestimate the running time
  - When running a support vector classifier model on the Fashion MNIST data, the running time was longer than initial expectation even I used Google colab, Machine Learning research tool supports GPU. It ended up completion after running over 10 hours.   

## Next Step
1. A project connecting Auto ML with AWS and Tableau for an entire Data Analytics architecture.
