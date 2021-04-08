# Fit Shot
Using the OpenCv, image processing technology, we have provided a virtual mirror (that will make use of the system's camera) for the users using which the user can undergo the “virtual try-on”. While trying on, it performs multiple tasks including detection of the user’s face from video stream, alignment of models, approximating the position of torso and lower body based on face detection and resizing input dress images and dress up using Image Processing. One can see how well the cloth of particular size fit to their body and experience whether or not the colour and other attributes of the clothing matches their liking.<br><br>
We have also provided a second module -‘GET YOUR MEASUREMENTS’.This module contains of two parts-  body edge detection and the body measurement.  Under this, the user can get their body edges traced and further, attempt to get their body measurements.The body is automatically detected and then, the edges of the body are detected. These edges then, form an actual sketch of the user’s body. 


## Motivation
One of the biggest challenges faced in being a part of the online fashion platform is the apparel fit. Due to limited fitting guides and no actual visualization, it is physically impossible for the user to try on clothes and see how they fit on them.<br>
In order to cope with this challenge and enhance the shopping experience, we aim to provide a way to find out the customer's actual body measurements and in order to use this functionality, they simply have to process their body in font of the camera and once this is done, the outline of their body will be traced and the measurements will be given as the output.<br>
Along with this, we're also providing a hassle free shopping by introducing a "virtual try on" of the apparels, using which the customers can undergo the actual garment fit. This will also help the buyer in finding best matches according to their body shape and help in resolving the 'misfit' issue that the online platform currently faces. 


## Use Instructions
Run the flasktry.py file by double clicking on the file or by typing flasktry.py on terminal. On the terminal you will find the port number on which it is running. On the browser type "http://localhost:'portno'" .. (port no is most of time '5000') and run it. The site will be loaded and On the main page, you can check out various shirts and pants from the navbar. <br><br>
By Clicking 'Predict' you will get options to select various shirts and pants to try on.After that on clicking "TRY" button, it will show you the result with the selected shirt and pant.<br>
By Clicking on "Get Measurement" you will be able to get your body measurements done through image processing and edge detection. Once successfully processed, the 2d measurements will begin to appear on the user’s window 

## Installation

`pip install opencv-python` <br>
`pip install flask` <br>
`pip install imutils` <br>
`pip install scipy` <br>
`pip install numpy`

## Prerequisites
Webcam/RGB Camera
(Keep your camera in a way where your body is fully visible for getting measurements and for Try-On keep the camera in way that your face could be detected)

## Technologies

* OpenCV 
* Flask


