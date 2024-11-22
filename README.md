# State Prediction From Indian Number PLate
State Prediction from Vehicle’s Number Plate is a Python-based app using OCR and image processing to detect the state of registration from number plates. Features include image upload, text extraction, and state mapping. Built with Flask, OpenCV, and EasyOCR, it supports applications like traffic monitoring, toll systems, and law enforcement.

## Features
Upload vehicle number plate images through a simple web interface.
Automatically detects, isolates, and extracts text from the number plate.
Maps the extracted text to predict the state name.
Deployed with Flask back-end and ngrok for easy access.

## Technologies Used
Python Libraries: OpenCV, EasyOCR, Flask, NumPy, Flask-CORS, imutils, and pyngrok.
Front-End: HTML5, CSS3, and JavaScript.


## Workflow
1. Image Upload: Users upload a number plate image.
2. Image Preprocessing:
     Convert the image to grayscale.
     Apply noise reduction and edge detection.
3. Contour Detection: Locate the number plate by identifying rectangular contours.
4. Masking and Cropping: Isolate and crop the number plate region.
5. OCR Processing: Use EasyOCR to extract text from the cropped number plate.
6. State Mapping: Map the extracted state code to its corresponding state name using a predefined dictionary.
7.Result Display: Display the predicted state name on the web interface.
