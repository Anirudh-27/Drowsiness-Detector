# Drowsiness Detector

### :cd: Dataset
* Few images with clear distinction of the eyes being open and closed.
* Can be video or images. But change code input format accordingly

### :key: Run the Code
* Save file as detect_drowsiness.py
* Open the code in the directory with the alarm and run it. 
* In order for the given code to work, "shape_predictor_68_face_landmarks.dat" file has to be downloaded from the dlib python package and placed in this directory. The default video stream for the given algorithm is a laptop webcam {i.e src=0} for testing purposes. However, you can change this according to your own usage and input whatever video stream you like for the code to detect.
* Main requirement for this code to work is to place the webcam or streaming device in a well lit area so it can detect facial features perfectly and give accurate results.

### :books: Libraries Used
* Numpys
* playsound
* time
* dlib
* CV2
* threading
* imutils
* scipy

### For more information please refer to the Project Report in this repository.
