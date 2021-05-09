Title: Gesture detection and classification to detect gestures that portray confusion. Using MediaPipe, LLE and KMeans clustering.

Dependencies:
-mediapipe
- cv2
- matplotlib.pyplot
- glob
- math
- numpy
- seaborn

Running:
1. Open terminal and Jupyter Notebook in the folder where the Zip File is extracted
2. Open file 'Pose classification using MediaPipe, LLE and KMeans' in Jupyter Notebook
3. 'Images' folder contains the images we use for training and testing
   'Images -> confused' contains the training data 
   All the folders in 'Images->confused' contain the data for a partical gesture/pose.
   'sampleOP' is the video used to generate frames for creating image set from a video (Used in Step 1:Part 2 in the notebook)
   'Images -> confused -> mixedsamples' contains all the images for each gesture including the images we get from the video 'sampleOP' we use to train the LLE based Kmeans model 
   'Images -> imtestsamples' contains the images we use for testing the Kmeans model
4. Some visualization (graphs and plots) are commented out, you may uncomment them as per requirement. 
   The report contains all the intermediate images' outputs if you do not want to uncomment.
5. Run all cells and view outputs at all stages.

