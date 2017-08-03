# Visual-Path-Prediction-TIP-2016

Dataset link: http://pan.baidu.com/s/1hsxfUz6 password: rx8x

These are two test datasets used for evaluation of visual path prediction algorithm. They are used in our paper [1] publicated on TIP 2016. All of the images, videos, and annotations of these two datasets are adapted from two video datasets, including VIRAT Video Dataset Release 2.0 [2] and KIT AIS Dataset [3]. If you use these datasets in your research, please kindly cite them:

[1] Huang S, Li X, Zhang Z, et al. Deep Learning Driven Visual Path Prediction From a Single Image[J]. IEEE Transactions on Image Processing, 2016, 25(12): 5892-5904.

[2] S. Oh et al., “A large-scale benchmark dataset for event recognition in surveillance video,” in Proc. IEEE Conf. CVPR, Jun. 2011,
pp. 3153–3160.

[3] B. Jutzi. (2016). Kit-ipf-Software and Datasets. [Online]. Available: http://www.ipf.kit.edu/english/code.php



These datasets are ONLY released for academic use. The copyrights belong to authors of [2] and [3].  

If you have any detail questions about the dataset, please feel free to contact us: siyuhuang@zju.edu.cn


## Introduction

test_images_VIRAT.zip and test_images_KIT.zip respectively include files of VIRAT set and KIT set. 

VIRAT set contains 43 folders corresponding to 43 raw videos of 9 scenes. The start indexes of each scene are (1, 3, 4, 12, 22, 28, 32, 35,41). Each folder contains three kinds of files: \*.jpg is scene image; bb_\*.mat is bounding-box of object with [w1, h1, w2, h2]; gt_\*.mat is trajectory of object with [h, w]. 

KIT set contains 8 folders corresponding to 8 scenes. The format of its files is the same to VIRAT set.

Please attention, the KIT set is only used for testing without training procedure. For VIRAT set, We only provide the files used for testing, because the size of training files is large and may be different for different algorithms. You can download the complete dataset in https://data.kitware.com/#collection/56f56db28d777f753209ba9f/folder/56f57e748d777f753209bed7 or http://www.viratdata.org/, and use the rest videos to generate training data according to the needs of your algorithm.

Thanks and hope you will benefit from these datasets.
