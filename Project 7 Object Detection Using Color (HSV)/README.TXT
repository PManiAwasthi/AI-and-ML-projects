This is a special project which does Object detection without the use of AI instead using predefined color callibrations.
Meaning that the program can be callibarated to recognize 1  HSV configuration so when an object resembling that same HSV value
is encountered i draws a circle around it and the circle size varies according to the distance of the object.

This project also has a python file to find HSV value of any object all you need to do is to open it and start messing around with the 
HSV value until only the object appears as white rest all things appear black on the side screen, note the HSV values.

now in the Object detection file change the hsv values so that the program knows what to find.
What this program does is that it takes the input from the camera and changes it to such a format that we can than compare the HSV values
once an object with similar values is encountered it find the centre of mass, area, contour and makes a circle using them.

I have made 2 variations 1 uses laptop camera other uses mobile camera.
