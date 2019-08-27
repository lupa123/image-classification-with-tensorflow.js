# image-classification-with-tensorflow.js
Transfer learning image classifier with a webcam

# About the project
I implemented a simple machine learning web application using TensorFlow.js.
I loaded and used a pretrained MobileNet model for classifying images from webcam. 
Then, I customized the model to classify images into three custom categories using k-nearest neighbors.
For more details about the  pretrained MobileNet model you can see https://observablehq.com/@nsthorat/how-to-build-a-teachable-machine-with-tensorflow-js


# Installation
Clone the repo

https://github.com/lupa123/image-classification-with-tensorflow.js.git

To run the webpage, simply open index.html in a Web Browser.

Now when you load the index.html page, you can use common objects or face/body gestures to capture images for each of the three classes. Each time you click one of the "Add" buttons, one image is added to that class as a training example. While you do this, the model continues to make predictions on webcam images coming in and shows the results in real-time.
