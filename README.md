CSCI_4120_HW_group_9 Machine Learning

Matt Carroll: carrollma16@students.ecu.edu

Mark Carroll: carrollma18@students.ecu.edu

Kevin Boyle: boylek19@students.ecu.edu

Homework one is located in HW1 folder, file KNeighborsClassifier.ipynb

We are importing pandas, random, matplotlib.pyplot and KNeighborsClassifier (from sklearn.neighbors) 

Which k works best?

We found that for k < 17, our accuracy rates are the same.  We notice that once k > 17, the accuracy of the model begins to decline.
We think that the accuracy is similar fewer lower k values because as the algorithm uses fewer neighbors, it has more data points that are close to the size of the flower, therefore the predictions are consistent.  As the algorithm uses more neighbors, the distance between the neighbors increases, and makes the prediction less accurate.  

