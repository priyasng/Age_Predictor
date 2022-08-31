
# Age Predictor - MACHINE LEARNING AND DEEP LEARNING PROJECT 

## Objective : Python program to build a model to predict age and gender of a person.

### About the Project :

Automatic age and gender classification has become relevant to an increasing amount of applications, particularly since the rise of social platforms and social media. With the advancement of technologies new features are added to our current using applications. One of such fun feature is to detect gender and age of a person who faces the camera at any instance. With the help of this project I tried to create a similar experience. The basic idea behind this project was to be able to understand the concepts of deep learning and neural networks.

In this Python Project, I had used Deep Learning to accurately identify the gender and age of a person from a single image of a face. The predicted gender may be one of ‘Male’ and ‘Female’, and the predicted age may be one of the following ranges- (0 – 2), (4 – 6), (8 – 12), (15 – 20), (25 – 32), (38 – 43), (48 – 53), (60 – 100) (8 nodes in the final softmax layer). It is very difficult to accurately guess an exact age from a single image because of factors like makeup, lighting, obstructions, and facial expressions. And so, I made this a classification problem instead of making it one of regression.

While traditional learning models analyse data using a linear approach, the hierarchical function of Deep Learning systems is designed to process and analyse data in a nonlinear approach.As new advances are being made in this domain, it is helping ML and Deep Learning experts to design innovative and functional Deep Learning projects.


## Model:

For basic training of the model I have used the VGG16 neural network architecture (CNN ) in order to make predictions on a given image. With the help of GUI I created an interactive page where the user can give inputs (image) and our model foretells the age and gender of the person in that image. 


## Dataset :

For this python project, I had used the Kaggle dataset; the dataset is available in the public domain and you can find it here. This dataset serves as a benchmark for face photos and is inclusive of various real-world imaging conditions like noise, lighting, pose, and appearance. The images have been collected from UTKFace albums. It has a total of 660000 photos of 2,284 subjects in eight age ranges (as mentioned above) and is about 347 MB in size. The models I used had been trained on this dataset.


## Technical Stack used:

Python, OpenCV, Kaggle, VS Code,Jupyter Notebooks, Image manipulation ,Tensor flow, Keras, Scikit, Matplotlib
                        
                
## Steps Involved:

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



## To simply run this model:
1. Clone the repository
2. Run the [gui.py](https://github.com/priyasng/Age_Predictor/blob/main/gui.py) file
3. Upload the Image you want to detect
4. Click on detect button
5. View results


## Sample Outputs:
### Sample Output 1:
![Sample Output 1](https://github.com/priyasng/Age_Predictor/blob/main/images/Sample%20output.png)

### Sample Output 2:
![Sample Output 2](https://github.com/priyasng/Age_Predictor/blob/main/images/Sample%20Output%202.png)

### Model Accuracy:
![Model Accuracy](https://github.com/priyasng/Age_Predictor/blob/main/images/model%20accuracy.jpeg)


### Predicted Age:
![ Predicted Age](https://github.com/priyasng/Age_Predictor/blob/main/images/predicted%20age.jpeg)

### Test Case :
![Test Case ](https://github.com/priyasng/Age_Predictor/blob/main/images/Test%20case%201.jpeg)


### As it is said “Knowledge is power - never stop learning”, I aim to do the same.  There is yet a lot to learn.Since the accuracy for this model came out to be 91% for Female and 87% for Male  for predicting age and gender ,so with the  aim  to increase the accuracy , in future i'll like to add more functionalities in this model. 




   
   

