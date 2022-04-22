# DL-Assignment2

![image](https://user-images.githubusercontent.com/16721983/164713940-66f1d06d-fec5-416c-ba92-7df5a3d31b30.png)
![image](https://user-images.githubusercontent.com/16721983/164713967-928291cf-be21-4601-829d-bc43b9d8f173.png)


Please refer to Page numbers 86 and 98 of Lecture Slide  
Chapter_2_CNN_Architectures_and_Transfer_Learning.pdf 

## LeNet5 Handwritten digits Classification in Pytorch 

LeNet5_MSIISE_MINST.ipynb or lenet5_msiise_minst.py in folder codes/ 

Trains LeNet5 using MINST train set.  
Validates trained model using MINST test set. 

Try following changes in LeNet5 architecture: 

ReLU instead of Tanh. 

MaxPool instead of AvgPool. 

Comment on the accuracy and the loss.  

 

Try different batch sizes : 128 and 512.  Comment on the result. 

 

Comment on the following observations: 

Try with large number of epoch and  observe train loss and validation loss.  

Observe the effect of learning rate in convergence and accuracy. 

 

Try different optimiser like Adam and  SGD with momentum and comment. 

 

Try LeNet5 (or any CNN of your choice on a dataset of Devnagari (Nepali)  
handwritten characters available at https://github.com/Prasanna1991/DHCD_Dataset.git 

 


## Transfer Learning Assignment 

Using transfer learning (feature extraction) in pyTorch, train a classifier that detects images of dogs using dataset available at https://github.com/moelgendy/deep_learning_for_vision_systems/tree/master/chapter_06/dogs_vs_cats_project 

 

Using transfer learning (fine-tuning) in pyTorch, build a sign language classifier that distinguishes 10 classes: the sign language digits from 0 to 9 using sign language dataset available at https://github.com/moelgendy/deep_learning_for_vision_systems/tree/master/chapter_06/sign_language_project 

 

Hint:  

Use Images in train/ folder for training, val/ folder for validation and test/ folder for testing. 

Load External data in colab https://colab.research.google.com/notebooks/io.ipynb 

 

You are free to choose any reasonable model pre-trained in ImageNet. Comment upon your choice. 

 

 Write your own custom data loader for PyTorch. 

 

Discuss about the optimization and parameters you have chosen. Comment on the learning rate you have selected for both cases. 

 

Discuss the transfer learning approaches you have chosen for both cases.. 

 
