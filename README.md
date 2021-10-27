# DigitClassifier

A simple Android app for classifying digits handwritten by users.

It was developed in two major steps.

## Step 1

Training an ML model using Tensorflow. 
The model was trained using the popular MNIST Dataset, which is dataset containing more that 60000 handwritten digits.
The model was converted to TensorFlow Lite to work in a mobile application.

## Step 2

Creating an android app that allow its users to handwrite any digit.
Then the trained model was loaded into the app to guess the number entered by the user.
