Face detection system
This Computer Vision project uses a haarcascade algorithm to detect and recognize its user's face. 
The program utilizes the mobile/laptop to first create a training dataset using the live images from the user, 
these are then in the later steps incorporated into training the model LBPHFaceRecognizer.
Once the training is finished the program takes in live feed from the mobile/laptop of the user as an input to detect 
and recognize the face of the user. In the output panel, the user can obtain real-time detection results embedded into 
the output stream of the live feed.

Libraries used are cv2, os, and numpy.
