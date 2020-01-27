# Project Report

<img src="images/feature_tracking.png" width="820" height="248" />

The SHITOMASHI detector along with BRIEF descriptor showed the best results in terms of time and keypoint matching accuracy.

The following is how the tasks of the projects were addressed:

* Data Buffer: Implemented a circular buffer using the mod operator.

* Keypoints: 
1. Implemented detectors HARRIS, FAST, BRISK, ORB, AKAZE, and SIFT, allowing the user to select which one to run by modifying a string.
2. Focussed keypoints in the area of the vehicle and drew a rectangle around the region of interest for visual clarity.

* Descriptors:
1. Implemented descriptors BRIEF, ORB, FREAK, AKAZE and SIFT.
2. Implemented Flann and K-nearest neighbor selection.
3. Implemented k-nearest neighbor with a threshold ratio of 0.8.

* Performance: The performance analysis data can be accessed under /data
1. Collected data on keypoints.
2. Collected data on all keypoint - descriptor combinations. 
3. Identified the top 3 combinations (highlighting in green) and identified the SHITOMASHI - BRIEF combination as the best. 

