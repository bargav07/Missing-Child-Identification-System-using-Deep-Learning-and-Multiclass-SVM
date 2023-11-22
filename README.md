# Missing-Child-Identification-System-using-Deep-Learning-and-Multiclass-SVM
In this paper author is describing concept to identify missing children by using Deep Learning and Multiclass SVM classifier and to implement this project author has used below modules

1)Using public dataset of missing children’s called FGNET is used to train deep learning CNN prediction model. After training model whenever public upload any suspected child image then this model will check in trained model to detect whether this child is in missing database or not. This detected result will store in database and whenever want official persons will login and see that detection result.

2)SVM Multiclass classifier use to extract face features from images based on age and other facial features and then this detected face will input to CNN model to predict whether this face child exists in image database or not.

First we used below dataset to train deep learning CNN model. pick images to train from test images in folder.

# To run project follow below steps
1) First create database in MYSQL by copying content from ‘DB.txt’ file and paste in MYQL
2) Install python, DJANGO and MYSQL software
3) Create ‘Python’ folder in C directory and put ‘MissingChilds’ folder in it
4) start DJANGO server and run in browser to get first page
