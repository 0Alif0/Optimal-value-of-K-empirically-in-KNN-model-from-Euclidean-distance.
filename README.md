# Optimal-value-of-K-empirically-in-KNN-model-from-Euclidean-distance.
The optimal value of K empirically in KNN model. Results  using  a  plot  with  training  and  test  errors
#![image](https://user-images.githubusercontent.com/29955878/192118413-e7f90aa7-e541-4e0e-97bd-b02f941d6ada.png)
In this homework, you will learn how to find the optimal value of K empirically in KNN model.
Show your results using a plot with training and test errors. To solve the problem, you need to
write a program. Use K = 1, 3, 5, 7, 9.
a)What is Knn? K-nearest neighbor is a non-parametric lazy learning algorithm, used for both
classification and regression. KNN stores all available cases and classifies new cases based on a similarity
measure.
b) How it does:
Step 1: Choose the number of K neighbors, say K = 5.
Step 2: Take the K = 5 nearest neighbors of the new data point according to the Euclidian distance.
Step 3: Among these K neighbors, count the members of each category.
Step 4: Assign the new data point to the category that has the most neighbors of the new data point.
Here it is the red category.
c) Some of the applications of Knn are:
 Text mining.
 Agriculture.
 Finance.
 Medical.
(a) Put Figure/Table number and Title: On top of the table, and
bottom of the figure
![image](https://user-images.githubusercontent.com/29955878/192118445-80c4ec55-21be-440a-a8cc-18605ea6da8a.png)
b)Describe results: With the KNN
Step 01: There is distance is given between two point.symmetric matrics put this into the list
Step 02: Make a data fram by panda
Step 03: Take these data colom wise which is given in the question.
Class 1: (x_1=0, x_2=1, x_5=5, x_6=6, x_9=7, x_10, x_13, x_14, x_17, x_18)
Class 2: (x_3, x_4, x_7, x_8, x_11, x_12, x_15, x_16, x_19)
Step 04: Each value need to be access and sorting the dictionary based on key values.Build model
without library.
Step 05: Ploting with the test and train error.K=4
(c) Your observation: Kvalue indicates the count of the nearest neighbors. We have to compute
distances between test points and trained labels points. Updating distance metrics with every iteration
is computationally expensive, and that’s why KNN is a lazy learning algorithm.
(d) Conclusion: KNN is one of the simplest forms of machine learning algorithms mostly used for
classification.
