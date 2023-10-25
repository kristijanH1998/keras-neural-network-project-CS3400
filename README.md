Abel Ortiz

Ben Ollar

Kristijan Hornung

CS 3400 : Final Project

The premise of this project is to explore deep learning networks and their applications. For this project, we created a system that detected whether a user is using a face mask or not. We used Tensorflow and Keras as the backend for the program and Jupyter Notebook as our development enviorment. This project was inspired by a tutorial posted to Data Flair, an online code tutoring site.

Our data set consisted of a set of images of people with masks and another set of people without masks. 658 images of people with masks were used to train the program and 97 images of people with masks were used to test the program. Additionally, 657 images of people without masks were used to train the program and 97 images of people without masks were used to train the program. 

To train the data we used two Dense layers. Our images were formated into vectors that could be utilized by the program. We used 10 epochs throughout this project. The final loss score was 0.1678 and the final accuracy was 0.9407 after the completion of the 10 epochs. The accuracy and loss scores would have improved if our dataset was increased

The test file is primarly used to access the user's webcam to test the program on the user's face. It uses the cv2 library for the webcam functionality. CV2 sends the live footage to the program to determine whether it detects a mask or no mask. It creates a box around the user's face that is outlined in red when the system detects a face without a mask. The box is outlined green when a face is detected with a facemask. 

Some issues we faced while working on this project was mainly with libraries. Tensorflow and Keras had some incompatabilities with our machines so we had to process some updates before starting our work. We also had some issues establishing the correct file paths to the data sets. Kristijan was the first to figure this out and helped guide. 
