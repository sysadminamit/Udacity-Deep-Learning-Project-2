# Udacity-Deep-Learning-Project-2

This is my second project on Udacity Deep Learning Nanodegree

The notebook into separate steps.

Step 0: Import Datasets
Step 1: Detect Humans
Step 2: Detect Dogs
Step 3: Create a CNN to Classify Dog Breeds (from Scratch)
Step 4: Create a CNN to Classify Dog Breeds (using Transfer Learning)
Step 5: Write your Algorithm
Step 6: Test Your Algorithm

# Step 0: Import Datasets
Make sure that you've downloaded the required human and dog datasets:

Download the dog dataset(https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip). Unzip the folder and place it in this project's home directory, at the location /dogImages.

Download the human dataset(https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip). Unzip the folder and place it in the home directory, at location /lfw.

# Step 1: Detect Humans
In this section, we use OpenCV's implementation of Haar feature-based cascade classifiers(http://docs.opencv.org/trunk/d7/d8b/tutorial_py_face_detection.html) to detect human faces in images.

OpenCV provides many pre-trained face detectors, stored as XML files on github(https://github.com/opencv/opencv/tree/master/data/haarcascades). We have downloaded one of these detectors and stored it in the haarcascades directory. In the next code cell, we demonstrate how to use this detector to find human faces in a sample image.

# Step 2: Detect Dogs
In this section, we use a pre-trained model to detect dogs(http://pytorch.org/docs/master/torchvision/models.html) in images.

# Step 3: Create a CNN to Classify Dog Breeds (from Scratch)
Now that we have functions for detecting humans and dogs in images, we need a way to predict breed from images. In this step, you will create a CNN that classifies dog breeds.

# Step 4: Create a CNN to Classify Dog Breeds (using Transfer Learning)

# Step 5: Write your Algorithm
Write an algorithm that accepts a file path to an image and first determines whether the image contains a human, dog, or neither. Then,

if a dog is detected in the image, return the predicted breed.
if a human is detected in the image, return the resembling dog breed.
if neither is detected in the image, provide output that indicates an error.

# Step 6: Test Your Algorithm
In this section, you will take your new algorithm for a spin! What kind of dog does the algorithm think that you look like? If you have a dog, does it predict your dog's breed accurately? If you have a cat, does it mistakenly think that your cat is a dog?
