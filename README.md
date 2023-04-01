# VIS-LWIR patch dataset   

### A brief introduction to the VIS-LWIR patch dataset
VIS-LWIR patch dataset patch dataset is an optical and LWIR image patch matching dataset with the patch size of 64 × 64 pixels based on [[paper(dataset)](https://ieeexplore.ieee.org/document/7789530)] and FAST keypoint extraction. The dataset contains a total of 21370 pairs of cross-spectral image patches with equal numbers of positive and negative samples. training set : test set=4 : 1 (17096 : 4274).   


### Document interpretation  
1. "finally_train.txt" denotes the image patch pair information of the training set.  
2. "finally_test.txt" denotes the image patch pair information of the test set .  
3. Each line in txt denotes a sample pair.  
4. Take one line as an example. The meaning of the corresponding position in "9,235,124,1" is "Original image name";"The serial number of the LWIR image patch";"The serial number of the optical image patch";"The label of the image pair. 1 for matching, 0 for nonmatching".  


### Construction of the dataset
1. Download raw data [[paper(dataset)](https://ieeexplore.ieee.org/document/7789530)].  
2. Build the corresponding dataset according to the image patch pair information in "finally_train.txt" and "finally_test.txt".








   


