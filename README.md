# Filtering-the-image
In this Project, I usually used OpenCV library for extracting different features of an image i.e; Gray Scale Image, Binary Image, Blue Image, Smoothing the image, Blurring the image, Detecting the edge of an image, adding Saturation in image, Converting the image into Green image, and other more features to an image.

### What is computer Vision? How computer reads an image?
Computer sees the image between 0-255 , for coloured images there will be 3 channels i.e;Red, Blue and Green and matrix 
associated with these channels and each elements of this matrix represents the intensity of brightness of that pixels.A 
computer interpret a coloured matrix as 3-D matrix.

## Library Used:

* Open Cv
* Numpy

## Features for converting the image
* Gray Scale Image
* Binary Image
* Blue Image
* Smothening the Image
* Bluring the Image
* Detecting the edge of image
* Saturation
* Green
* Red
* Value
* Cropping the image
* Doubling the image
* Transposing the image
* Detecting the Face in an image
## Image processing
For face detection we need a image and after that we have a cascade classifier ,it contains the features of face.The OpenCV
will be read the image and feature the file i.e; convert into NumPy array and search for the row and column values of the 
face NumPy ndarray (The face rectangular coordinates)and display the image with rectangular box.
