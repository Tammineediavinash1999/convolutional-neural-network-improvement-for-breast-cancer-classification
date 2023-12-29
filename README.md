# CONVOLUTIONAL NEURAL NETWORK FOR BREAST CANCER CLASSIFICATION

In the earlier CNN models, the model is only used to classify whether the
cancer is present or not, but that model didn't know the level of cancer if it
is present. Further models were build to classify the breast cancer as bengin,
malignant or healthy. This type of classi cation helps the doctors to give
appropriate treatment to the patient based on the level of breast cancer. So,
there will be better chances for the patient to survive if patient is given the
appropriate treatment. This model also accounts for the increase in accuracy
than that of the previous models.

# Problem Statement 1
Convolution Neural Network based classifier
model is build so as to classify the mammograms as Benign, Malignant or
healthy person. This model just simply implements direct mammograms of
benign,malignant and healthy people without any pre-processing.
Input : mammogram of size 1024 X 1024 pixels
Output : Benign ,malignant,or healthy person.

# Problem Statement 2
Preprocessing the benign and malignant mammograms to build a CNN model. This process cannot preprocess the healthy
patient mammogram as they donot have any lesions.
Input : 1024 x 1024 pixel Mammogram image.
Output: 8 images each of size depending on radius of the lesion.

# Problem Statement 3
Build a CNN model to classify benign or malignant using preprocessed images. Compare the accuracies of CNN models
without image pre-processing and with image pre-processing.
Input : Pre-processed mammograms
Output: Benign, malignant.
