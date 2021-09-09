CSCI_4120_HW_group_9 Machine Learning

Matt Carroll: carrollma16@students.ecu.edu

Mark Carroll: carrollma18@students.ecu.edu

Kevin Boyle: boylek19@students.ecu.edu

Homework one is located in HW1 folder, file KNeighborsClassifier.ipynb

We are importing pandas, random, matplotlib.pyplot and KNeighborsClassifier (from sklearn.neighbors) 

Which k works best?

We found that for k < 17, our accuracy rates are the same.  We notice that once k > 17, the accuracy of the model begins to decline.
We think that the accuracy is similar fewer lower k values because as the algorithm uses fewer neighbors, it has more data points that are close to the size of the flower, therefore the predictions are consistent.  As the algorithm uses more neighbors, the distance between the neighbors increases, and makes the prediction less accurate.  

Line Charts for various executions of knn algorithm using KNeighborsClassifier
![image](https://user-images.githubusercontent.com/16233572/132776079-a3c7cb57-d34f-4775-bcab-ec2edc0392e9.png)

![image](https://user-images.githubusercontent.com/16233572/132776104-1c31f831-03a5-4159-8f16-0811c71e89c5.png)

![image](https://user-images.githubusercontent.com/16233572/132776125-31a8e852-3304-4686-97b4-799b5e710927.png)

![image](https://user-images.githubusercontent.com/16233572/132776215-80e2f540-e6f6-4510-92c1-f90203d38f48.png)

