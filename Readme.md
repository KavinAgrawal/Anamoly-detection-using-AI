DATASET:

The dataset can be also downloaded from the following link:
https://visionlab.uncc.edu/download/summary/60-data/477-ucf-anomaly-detection-dataset

The implementation is tested using:
Keras version 1.1.0
Theano 1.0.2
Intel distribution for Python 3
Ubuntu 16.04

We used C3D-v1.0 with default settings as a feature extractor.
 
Training_AnomalyDetecor_public.py is to Train Anomaly Detection Model
Testing_Anomaly_Detector_public.py is to test trained Anomaly Detection Model
Save_C3DFeatures_32Segments is to save already computed C3D features for the whole video into 32 segment features.
weights_L1L2.mat: It contains the pre-trained weights for the model ‘model.json’.
Demo_GUI: We have provided a simple GUI which can be used to see results of our approach on sample videos.
SampleVideos: This folder contains C3D features (32 segments) for sample videos. It order to see testing results for the features in this folder, please copy the corrosponding videos in the same folder.
Plot_All_ROC:  This code can be use to plot the ROC results reported in the paper. The data to plot ROCs of methods discussed in the paper can be found in folder Paper_Results.

Temporal_Anomaly_Annotation.txt contains ground truth annotations of the testing dataset.
Anomaly_Train.txt contains the video names for training anomaly detector