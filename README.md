# INDEPENDET STUDY
This is an independent Study to run supervised machine learning on fashion mnist data. It was proceeded under the supervison of Prof. Andrew Catlin, Program Director of Data Analytics and Visualization at the Katz School, Yeshiva University.


This independent study(IS) aims to learn supervised machine learning using scikit-learn and comparing the accuracy score of the results with the results of running a model by DataRobot, an auto machine learning(AutoML) tool. For the dataset, Fashion MNIST and MNIST datasets are used. 

This IS starts with learning supervised machine learning by using Scikit-learn as a machine learning tool. 

[Sources]
- Datacamp: Supervised Learning with scikit-learn (https://www.datacamp.com/courses/supervised-learning-with-scikit-learn)
- Hands on Machine Learing with Scikit-Learn & TensorFlow (https://github.com/ageron/handson-ml)

[Datasets]
- Fashion_MNIST (https://www.kaggle.com/zalando-research/fashionmnist)
- MNIST (http://yann.lecun.com/exdb/mnist/)

[Tools]
- Scikit-Learn(https://scikit-learn.org/stable/) 
- Google Colab(https://colab.research.google.com/notebooks/welcome.ipynb)
- Data Robot(https://www.datarobot.com/)


## Steps
1.For the beginning, I run a classification model on MNIST data (https://github.com/jeehobdata/Fashion_Mnist/blob/master/Recognizing%20hand-written%20digits%20by%20Scikit-learn.ipynb)

2.Secondly, run the classification model used on the previous datset on Fashion MNIST data (Used Google Colab) 
(https://github.com/jeehobdata/Fashion_Mnist/blob/master/tensorflow2beachhead.ipynb)

3.Run DataRobot
(To run The DataRobot, only test set of the Fashion MNIST data is used and 14 models ran out)
- As the result,  _Light Gradient Boosted Trees Classifier with Early Stopping (SoftMax Loss) (16 leaves)_ shows recommended for deployment with 87.09% of accuracy , while _AVG Blender_ show the most accuracy score as 87.14%. _TensorFlow Neural Network Classifier_, also had a high accuracy score as 85.59% 

## Key Takeaways
1. Classification Model Accuracy Validation
  - Accuracy score and hamming Loss are a way to measure the accuracy or classification models. 
  - In Scikit-learn, ROC_AUC method does not support classification mode. 
 
2. DataRobot, other Auto AI saves lots of time
  - Based on uploaded dataset, DataRobot detects and applies number of available Machine Learning models for the given datasets at the same time. By that approach, the users can see results of each models without running the models one by one, so that the users could choose the most appropriate model among the list by simply comparing them.

3. Never underestimate the running time
  - When running a support vector classifier model on the Fashion MNIST data, the running time was longer than initial expectation even I used Google colab, Machine Learning research tool supports GPU. It ended up completion after running over 10 hours.   

## Next Step
1. A project connecting Auto ML with AWS and Tableau for an entire Data Analytics architecture.
