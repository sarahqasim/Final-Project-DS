# Final-Project-DS

This project aims to bridge that gap by developing a computer vision-based system that translates American Sign Language (ASL) hand gestures into text. 
ASL is a common type of sign language form used in North America with different hand gestures and motions. 
The model will classify images of hand gestures and map them to corresponding letters of the alphabet.

Dataset: The Sign Language MNIST dataset was used, containing labelled images of ASL hand gestures.
A Convolutional Neural Network (CNN) was implemented using TensorFlow and Keras for feature extraction and classification.


## Installation & Setup

### **1. Clone the Repository**

git clone https://github.com/sarahqasim/Final-Project-DS.git
cd Final-Project-DS

pip install -r requirements.txt 

### Features  
- Detects and classifies sign language from hand gesture images
- works with a preset dataset of images  
- Uses computer vision algorithm (CNN) for classification.

### Importing libraries:
-	Numpy and pandas for data processing and manipulation
-	Matplotlib and seaborn for visualisation
-	We used the models and layers subpackages from Keras to import the Sequential model and Conv2D, MaxPool2D, Flatten, Dense and Dropout layers for building the neural network.
Importing Dataset
-	The mnist train and test zip files were imported from Kaggle.
-	The files were uploaded on Google Collab file, unzipped using the 
-	!unzip method which was then stored in the cloud along with the zipped versions. These files were then read as train_df and test_df using pandas’ read_csv function.





