This is an object recognition project using the computer vision concept of frame comparison.
This is a non AI way to recognize an object in real time.
The programming language used is python.
The libraries are cv2, numpy, imutils.
cv2 is used for video capturing and performing various image processing functions on the feed received.
I used functions like cv2Color, absdiff, GaussianBlur, threshold, dilate, findContours, grab_contours to detect and get the coordinates of the moving object. For creating the bounding box I used contourArea, bouddingREct, rectangle, putText.
The program can be opened in the Juputer notebook and contains all necessary explanations in commented form.
