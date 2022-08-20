
MACHINE LEARNING AND DEEP LEARNING PROJECT- Age and Gender Predictor

Objective : Python program to build a model to predict age and gender of a person.

About the Project :

Automatic age and gender classification has become relevant to an increasing amount of applications, particularly since the rise of social platforms and social media. With the advancement of technologies new features are added to our current using applications. One of such fun feature is to detect gender and age of a person who faces the camera at any instance. With the help of this project I tried to create a similar experience. The basic idea behind this project was to be able to understand the concepts of deep learning and neural networks.

In this Python Project, I had used Deep Learning to accurately identify the gender and age of a person from a single image of a face. The predicted gender may be one of ‘Male’ and ‘Female’, and the predicted age may be one of the following ranges- (0 – 2), (4 – 6), (8 – 12), (15 – 20), (25 – 32), (38 – 43), (48 – 53), (60 – 100) (8 nodes in the final softmax layer). It is very difficult to accurately guess an exact age from a single image because of factors like makeup, lighting, obstructions, and facial expressions. And so, I made this a classification problem instead of making it one of regression.

While traditional learning models analyse data using a linear approach, the hierarchical function of Deep Learning systems is designed to process and analyse data in a nonlinear approach.As new advances are being made in this domain, it is helping ML and Deep Learning experts to design innovative and functional Deep Learning projects.


Model:

For basic training of the model I have used the VGG16 neural network architecture (CNN ) in order to make predictions on a given image. With the help of GUI I created an interactive page where the user can give inputs (image) and our model foretells the age and gender of the person in that image. 


Dataset :

For this python project, I had used the Kaggle dataset; the dataset is available in the public domain and you can find it here. This dataset serves as a benchmark for face photos and is inclusive of various real-world imaging conditions like noise, lighting, pose, and appearance. The images have been collected from UTKFace albums. It has a total of 660000 photos of 2,284 subjects in eight age ranges (as mentioned above) and is about 354 MB in size. The models I used had been trained on this dataset.


Technical Stack used:

Python, OpenCV, Kaggle, VS Code,Jupyter Notebooks, Image manipulation ,Tensor flow, Keras, Scikit, Matplotlib
                        
                
Steps Involved:

1.Importing libraries and dataset:

  Additional Python Libraries Required :
  OpenCV
      pip install opencv-python
  NumPy
      pip install numpy
   

2.Data pre-processing

3.Splitting dataset

4.Applying VGG16 model for Gender

5.Applying VGG16 model for Age
   
6.Model evaluation 

7.Open CV

8.Creation of GUI


 
As it is said “Knowledge is power - never stop learning”, I aim to do the same.  There is yet a lot to learn.Since the accuracy for this model came out to be 85% for Gender and 70% for Age,so with the  aim  to increase the accuracy , in future i'll like to add more functionalities in this model . 


Reference
[1] Rothe R, Timofte R, Van Gool L. Deep Expectation of Real and Apparent Age from a Single Image Without Facial Landmarks [J/OL]. International Journal of Computer Vision. 126 (2). 2018, Apr: 144–157.




   
   

