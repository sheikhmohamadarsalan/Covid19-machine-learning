# covid19-detection
This code is for predicting COVID-19 from chest Xrays. The model currently has 95% accuracy.The python notebook attached contains the code for training and testing.


# Dataset
The dataset was collected from many sources. Currently this git repo is maintaining the COVID-19 Xray dataset:
https://github.com/ieee8023/covid-chestxray-dataset

Dataset was divided into 2 classes: COVID-19 and Other.

# Model Statistics and Accuracy
VGG16 model was utilized as base model, the layers were freezed and on top of it some more layers were added. The model was trained on 370 samples of data and tested on 36 samples. The testing accuracy currently reported is 95%.

![ROC curve of model](https://github.com/hananshafi/covid19-detection/blob/master/covid-roc.png)

![Confusion matrix](https://github.com/hananshafi/covid19-detection/blob/master/cmatrix.JPG)


# Here is the the result of model on one of the samples:

![X-Ray of COVID-19 Positive patient](https://github.com/hananshafi/covid19-detection/blob/master/covid-19.JPG)
