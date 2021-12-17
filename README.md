# Dog-Breed-Classification
Identifies breed of dog using CNN

 We are provided with a training set and a test set of images of dogs. Each image has a filename that is its unique id. The dataset comprises 120 breeds of dogs. The goal is to create a classifier capable of determining a dog's breed from an image.
 
 For the sake of a more efficient model, we reduced the total number of unique breeds from 120 to 60 and took only 5 unique breeds (classes) into consideration for training the  CNN Model.
 
*building the model using ResNet50V2.*
 
 <p align="center"> 
<img width="285" alt="resnet50v2" src="https://user-images.githubusercontent.com/86421205/146565897-da5329d5-dc09-4f93-a685-6e7cc1ed60a6.jpg">
</p>

 Got a decent accuracy. We can improve the accuracy by increasing the number of epochs to 100 or 500. Also we can consider tuning the hyperparameters.
