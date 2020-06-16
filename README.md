
# Facial Expression Recognizer 
A program built using tensorflow, Adam and Flask to set up a basic website on localhost port 5000
that uses your video camera to identify what mood you're in. 

To run it - ensure you have pipenv installed:
1. ```pipenv install```
1. pipenv run python3 main.py

## Possible Issues
If the webcam causes any issues, you can change the ```cv2.VideoCapture``` line in ```camera.py``` and pass in the path to any file
you would like to use. There are 2 examples in the videos folder.
