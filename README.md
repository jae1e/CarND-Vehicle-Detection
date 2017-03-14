# Vehicle Detection

The goals / steps of this project are the following:

* Perform a Histogram of Oriented Gradients (HOG) feature extraction on a labeled training set of images and train a classifier Linear SVM classifier
* Optionally, you can also apply a color transform and append binned color features, as well as histograms of color, to your HOG feature vector. 
* Note: for those first two steps don't forget to normalize your features and randomize a selection for training and testing.
* Implement a sliding-window technique and use your trained classifier to search for vehicles in images.
* Run your pipeline on a video stream (start with the test_video.mp4 and later implement on full project_video.mp4) and create a heat map of recurring detections frame by frame to reject outliers and follow detected vehicles.
* Estimate a bounding box for vehicles detected.

HOG feature extraction
---

Before extracting HOG features, I converted image channel from RGB to YCrCb which showed the best performance after the HOG feature extraction. Then HOG feature extraction was carried out. The image below shows the result of HOG feature extraction.

* HOG feature extraction image

Sliding window search
---




Result
---



Discussion
---


