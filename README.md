The Dataset Used In The Above Program Is provided by Dr. Yoshua Bengio of the University of Montreal. On Kaggle And The Link To The 
Dataset Is : https://www.kaggle.com/c/facial-keypoints-detection/data

Methodology

Data from the dataset was augmented by flipping the images and their keypoints. 
I then used a CNN as the feature extractor, flattened the outputs and passed them into a fully connected ANN to perform facial keypoint regression.

Once the model was complete, I used OpenCV to get live data from the webcam for real-time predictions.  
Then I used the positions of specific keypoints for the position and scale of 'filters' on top of the image.
