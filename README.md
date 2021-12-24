# Kaggle-bottle-classification

A python notebook describing the training process of two parallel CNNs (ResNet-50V2 and InceptionV3) using data augmentation, transfert learning, fine tuning and TTA.

An internal data set on bottle content percentages was provided for the challenge:

- kaggle_train_128.zip - the training set. It contains 15000 images (3000 for each class), each of size 128*128. After extraction, there will be 5 sub-folders. The name of the sub-folder is the corresponding class.

- kaggle_test_128.zip - the test set. It contains 3500 images, each of size 128*128.
