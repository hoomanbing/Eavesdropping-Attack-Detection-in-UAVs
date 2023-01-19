# Eavesdropping-Attack-Detection-in-UAVs
The use of unmanned vehicles(UAV) have proliferated and are prone to cyber attacks. Eavesdropping attack is an active threat to the security of an UAV as attackers can intercepts the communication medium over the wireless communication networks and get access to sensitive information. An active eavesdropper can infiltrate the system and attack the UAV during authentication. For the detection of eavesdropping attacks, we built an ensemble learning model with machine learning classification algorithms and unsupervised one-class support vector machines (OC-SVM) and K-means clustering. To train our proposed model we have used Kitsune Network Attack Dataset. We prove that our ensemble learning approach is a valid stratagem that can be used to detect eavesdropping attack on UAV.
## Architecture of our proposed model
An ensemble learning model is designed by us where we have chosen some common machine learning algorithms which include logistic regression, kNN, SVM, decision tree and random forest. The model having highest accuracy has been obtained and is used to ob- tain the optimal detection results. An unsupervised machine learning model has also been designed comprising K-Means Clustering and One-Class SVM.
![UAV_new (1)](https://user-images.githubusercontent.com/91937177/213416372-817b39a4-e713-4b96-bf3d-7a5dc269ae3d.jpeg)
1) Taking Kitsune Network Attack Dataset as input data.
2) Using the preprocessing modules and MinMaxScaler to decrease large variation in data.
3) The data is divided into 80% train data and 20% test data.
4) The training data is used to train both the supervised and unsupervised models.
5) The test data is used on each algorithm to output the preliminary predict classification and calculate result using the most accurate algorithm.
![accuracies](https://user-images.githubusercontent.com/91937177/213416652-a121b048-ce96-443b-934a-2a67f8857963.png)
![unsupervised](https://user-images.githubusercontent.com/91937177/213416732-3971b136-f872-443f-b1c4-e106bde10209.png)
### Dataset Used
