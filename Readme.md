Methodology
This model is taking input from the webcam of your computer and then at each timestep:-
It pre-process the image to remove noises and crop image to take only region which is of interest to us.
Detect edges of hand by using Canny's Edge Detection.
Apply HOG(Histogram Of Oriented Gradients) to extract useful features from edge detected image.
Use extracted features to predict gesture by trained SVM model.
