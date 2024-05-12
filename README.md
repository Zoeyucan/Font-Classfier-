# Create a Font Classfier - using ResNet model

## 1. pre-processing dataset

read./project_files/data file and 10 classes fonts images，Crop and scale the data image set to 100*100, then rotate it randomly 3 times, expand the dataset, and save it to the./dataset/dataset folder.

## 2. split train-test dataset

The dataset 8:2 is divided into the training set and the test set, which are saved in the train and test folders respectively.

## 3. Build ResNet model and train output accuracy, loss value and time. Save the best model best-pth and the last step model last.pth.

## 4. Evaluate model

The loss curve and the accuracy curve are drawn.

##### Accuracy for each class

##### precision，recall, and f1-score

##### confusion matrix
