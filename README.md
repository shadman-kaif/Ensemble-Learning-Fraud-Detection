# Ensemble-Learning-Fraud-Detection

Final Capstone Project for ECE496.

Group Members: Shadman Kaif, Abdurrafay Khan, Krutarth Patel, Shanthosh Sivayogalingam

Dataset: 

**Executive Summary**

The motivation behind this project stemmed from the importance of credit card transaction processing standards keeping in line with the growth of e-commerce. With clear indications of a growing trend in consumer habits and credit card usage, it is imperative that banks are able to authenticate and approve genuine transactions and accurately reject those that could be fraudulent. Even with the current state-of-the-art machine learning (ML) models, $118 billion was lost due to false positives in 2014 and these models only show a 78% accuracy when distinguishing between fraud and legitimate transactions. That is why the goal of our project was to create a linearly classifiable ensemble ML algorithm that minimizes the number of false positives to at least 20-30% in a credit card dataset. 

The objective of this project was to design a solution that also achieves an accuracy of 95% while being able to process at least 65,000 transactions/sec. Late additions to these objectives were meeting a recall score of at least 50% and a false negative rate below 30%. The team had to complete this design solution considering constraints such as being limited to simulated transaction data for privacy and security reasons as well as not being able to process real-time data without a history of transactions for the model to learn from. Ultimately, the team was able to find an optimal ML model using the AdaBoost ensemble learning method.

Through various iterations of tuning different hyperparameters, the team finalized the optimal design solution to be an AdaBoost model with a learning rate of 1.0, 10 estimators and a probability threshold of 50%. This final model produced the best results in minimizing false positives, keeping false negatives low while also not sacrificing a high accuracy. From the testing and verification the model only failed to meet the goal of processing at least 65,000 transactions/sec but speed was the team’s least valued objective because it is strongly correlated to hardware.

Overall, the final model is ready and can be used in the backend of a bank system to better combat fraud. The AdaBoost model outperformed current state-of-the-art models as expected with respect to false positives. The team does understand that the testing and verification could have accounted for other variations of the AdaBoost model which use different estimators which could lead to better results. Future adaptations of this project can be to develop this model to assist fraud in other financial sectors such as insurance or loans.

**Capstone Poster**
![alt text]("https://github.com/shadman-kaif/Ensemble-Learning-Fraud-Detection/blob/main/Poster_picture.png?raw=true")
