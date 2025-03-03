# Hand Gesture Recognition Using SVM

## Methodology

This model takes input from the webcam of your computer and, at each timestep, performs the following steps:

### 1. Pre-processing  
- Removes noise from the image.  
- Crops the image to focus only on the region of interest (hand area).  

### 2. Edge Detection  
- Uses **Canny’s Edge Detection** to identify the boundaries of the hand.  

### 3. Feature Extraction  
- Applies **Histogram of Oriented Gradients (HOG)** to extract useful features from the edge-detected image.  

### 4. Gesture Prediction  
- Uses the extracted HOG features as input to a **trained Support Vector Machine (SVM) model** to classify the gesture.  

This model enables real-time hand gesture recognition for various applications.
