
## 1. Context
Skin cancer is one of the most common malignancies in humans. Early detection would require less medical intervention and there is a better survival rate if detected early.
With the aid of machine learning we would be able to train deep learning models and build automated system to classify skin lesions Images.

## 2. Objective
Using the HAM1000 data set from Kaggle we are trying to build predictive deep learning model using Convolutional Neural Network (CNN) to classify the skin cancer images.

##3. Method
The entire project was implemented in python on Google collab which is built in a pipeline structure with Tensorflow and Keras modules. 
The implemented Convolutional Neural Network (CNN) models are VGG16 and ResNet50V2, which can classify 7 different types of skin cancer lesions.

Important considerations before reproducing the work.
•	This Project is built on Google Collab as it requires GPU to train our models
•	Running the whole project while trying to train the model will take some time.

## 4. Steps to execute this Project.
1.	Download and load the .ipynb file on to you google Collab
2.	Change the Run time to GPU from None. This will reduce the training time getting a GPU assigned.
3.	The Project is built like a pipe-line in a sequential format. All the cells should be executed one after the other. All folder structure that are required are created as you execute the cells.
4.	The required packages and models required is already present in the code. (You can also refer to requirement.txt if required)
5.	The data set will be downloaded from the Kaggle. To do so download the Kaggle API token from you Kaggle account by following the steps below and place it in the collab environment (/content/).
6.	Go to your account, Scroll to API section and Click Expire API Token to remove previous tokens
7.	Click on Create New API Token - It will download kaggle.json file on your machine.
8.	Place the kaggle.json it in the Collab environment  path (/content/)

Note: If you are not able to follow the above process, follow the in-line instructions in the code to load the data in the alternative way.

9.	Under Data Set loading section execute the first cell and click on choose file to upload the Kaggle.json API that was downloaded from the previous step. This will download the data set directly to collab
10.	The rest of the steps can be executed one after the other (Some steps may take time to execute, please wait patiently) to reproduce the plots and see the analysis performed with the results.
11.	All the explanation and In-line comments are placed as a mark down.
12.  The trained  model weights for both vgg16 ang resNet50 are placed under Model_weights folder 
12.	The same .ipynb file has been converted to pdf and html for report.(consider using html format has beeter print lay out)

## 5.The list of contents/ sections for the report and code is as follows:

**Table of Content**

1. Abstract
2. Introduction
3. Data Set Overview
4. Dataset Loading 
5. Data Preprocessing
6. Numerical and Viziual Exploratary Data Analysis
7. Data Engineering
8. Model Building
    
    Image Augmentation 
    Class Weights 
    Evaluation Metric 
    Transfer Learning 
    VGG16 
    ResNet50v2
9. Results & Conclusion
10. Future Scope
11. Personal Reflection
12. References 

