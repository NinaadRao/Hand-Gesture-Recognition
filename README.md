# Hand-Gesture-Recognition

## Dataset Link: https://www.kaggle.com/gti-upm/leapgestrecog
The database is composed by 10 different hand-gestures (showed above) that were performed by 10 different subjects (5 men and 5 women).
1.The different classes were:<br>
2. palm<br>
3. l<br>
4. Index<br>
5. Fist_moved<br>
6. c<br>
7. ok<br>
8. down<br>
9. thumb<br>
10. palm_moved<br>
11. Fist<br>

This repository aims to classify hand gestures. There are various uses to it such as aiding communication for the deaf. It can also be used for gaming devices such as the Microsoft Kinect. Our dataset is comprised of infrared images obtained by a Leap Motion sensor. The dataset consists of 10 different hand gestures. There are 10 subjects, 5 male and 5 female. There are a total of 20000 images. Thus, an image should be classified into one of the 10 classes. 

This repository builds a hand gesture recognition model using two approaches:
1. CNN based approach<br>
2. Ensembled based approach<br>
The main aim of this repository is to have a comparative study between the two approaches.

The first step in classification is preprocessing. Since the dataset was a collection of hand gesture images, detecting the hand was the first task. For detecting the hand, we used OTSU’s binarization technique and converted all the images into black and white images.

Principal Component Analysis(PCA) was done for the images and reduced to 4 dimensions for easier processing in emsembled approach.


The models that were considered for this approach are:<br>
1.Stochastic Gradient Classifier<br>
2. K Nearest Neighbour<br>
3. Decision Tree<br>
4. Random Forest Tree<br>
5. Logistic Regression<br>
6. Naive Bayes<br>
7. Artificial Neural Network<br>
8. Gradient Descent Classifier<br>
9. Support Vector Machine<br>

Stacking and Voting Based Classifiers were used to combine the models.<br>
