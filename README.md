# Machine learning Model to predict the Failure of Machine parts

# Overview
A manufacturing company decides to invest in proactive maintenance methods to reduce expensive unexpected breakdowns.In the maintenance process, asset's health, status, and performance in real time are tracked. Based on the tracked details, build a model to predict failure of machine parts.The main task is to create a predictive model that can determine whether the machine will fail and if it is failing then what type of Failure .

# Software Environment
* Python 
* numpy 
* scipy	
* matplotlib 
* scikit-learn 
* pandas

# Data Summary
The dataset predictive_maintenance.xlsx consists of 10,000 data points stored as rows with 14 features in columns.
* UID: unique identifier ranging from 1 to 10000
* productID: consisting of a letter L, M, or H for low (50% of all products), medium (30%), and high (20%) as product quality variants 
* air temperature [K]: This is the air temperature generated from the machine
* process temperature [K]: generated using a random walk process normalized to a standard deviation of 1 K.
* rotational speed [rpm]: calculated from powepower of 2860 W, overlaid with a normally distributed noise
* torque [Nm]: torque values are normally distributed around 40 Nm with an Ïƒ = 10 Nm and no negative values.
* tool wear [min]: The quality variants H/M/L add 5/3/2 minutes of tool wear to the used tool in the process. 
* Target : Failure or Not
* Failure Type : Type of Failure
![image](https://user-images.githubusercontent.com/132809858/236670827-452abe14-12e1-4151-829a-1782e98481dc.png)

# Results:
Model Comparison and Oversampling

![image](https://user-images.githubusercontent.com/132809858/236671658-d9e09c0b-f2f2-4519-a244-ed6c7c283e71.png)

Undersampling

![image](https://user-images.githubusercontent.com/132809858/236672058-7d64a093-0295-48a2-b32e-605b46b88337.png)












