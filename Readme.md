#Methodology
This model is taking input from the webcam of your computer and then at each timestep:-
1.It pre-process the image to remove noises and crop image to take only region which is of interest to us.
2.Detect edges of hand by using Canny's Edge Detection.
3.Apply HOG(Histogram Of Oriented Gradients) to extract useful features from edge detected image.
4.Use extracted features to predict gesture by trained SVM model.
