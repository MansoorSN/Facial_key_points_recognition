# Facial_key_points_recognition

This project was built using the dataset from the facial key points detection Project from [Udemy Nano degree: Become a Computer Vision Expert](https://www.udacity.com/course/computer-vision-nanodegree--nd891) .

The dataset consists of images of faces with *68 keypoints* (x,y coordinates) that depict the **facial features** like *eyebrows, eyes, nose, mouth, face outline*. 
We train a *Convolutional Neural Network* to detect the facial keypoints for the image input given.

1. Transfer Learning was applied on a pretrained [**DenseNet121**](https://www.tensorflow.org/api_docs/python/tf/keras/applications/DenseNet121) model available in tf.Keras to predict the facial keypoint coordinates. I have experimented by keeping all the layers in the densenet model trainable, except the last convolutional layer and [also by keeping all the layers trainable](https://github.com/MansoorSN/Facial_key_points_recognition/blob/master/facial_keypoint_detector_using_densenet.ipynb). The later performed better of the 2 models.

2. 
