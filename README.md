# hpc-cell-identification-challenge

Our approach is three fold:

(1) CellProfiler for segmentation and feature extraction + Random Forest for classification

(2) Graph partitioning for segmentation + SPADE for feature extraction + Random Forest for classification

(3) Graph partitioning for segmentation + Deep Learning for patch level classification + majority vote


Through holdout validation, each of the above methods exhibited similar accuracy, but made different mistakes. The impression is the prediction accuracies among the three approaches are (3)>(1)>(2). 

Two sets of results are submitted to the challenge. One is the ensemble of the three approaches. The other is just approach (3). 

