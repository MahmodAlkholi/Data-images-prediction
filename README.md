# Data-images-prediction
50000 images converted to numpy arrays and applied models on it
# cifar-10 Dataset content 50000 images
Data Link on Kaggle (https://www.kaggle.com/c/cifar-10)
The CIFAR-10 data consists of 60,000 32x32 color images in 10 classes, with 6000 images per class. There are 50,000 training images and 10,000 test images in the official data. We have preserved the train/test split from the original dataset

To discourage certain forms of cheating (such as hand labeling) we have added 290,000 junk images in the test set. These images are ignored in the scoring. We have also made trivial modifications to the official 10,000 test images to prevent looking them up by file hash. These modifications should not appreciably affect the scoring. You should predict labels for all 300,000 images.
############################################################################################################################################################

The label classes in the dataset are:

airplane 
automobile 
bird 
cat 
deer 
dog 
frog 
horse 
ship 
truck

The classes are completely mutually exclusive. There is no overlap between automobiles and trucks. "Automobile" includes sedans, SUVs, things of that sort. "Truck" includes only big trucks. Neither includes pickup trucks.

as showen in the notebook all images converted to numpy arrays and stored into dataframe .
after that data splited in to train , validation and test .
I applied (KNN, RandmForest) models but it did not give a a good accuracy .
so after all we need to apply (neural network) on the dataset .
