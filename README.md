# SCALABLE MULTI-CONSISTENCY FEATURE MATCHING WITH NON-COOPERATIVE GAMES (ICIP 2018)
***

This repository is a reference implementation for Chen Zhao, Jiaqi Yang, Yang Xiao and Zhiguo Cao, "SCALABLE MULTI-CONSISTENCY FEATURE MATCHING WITH NON-COOPERATIVE GAMES", ICIP 2018.

# Citation
***
If you find our work useful in your research, please consider citing:
```
@inproceedings{zhao2018scalable,
    title={Scalable Multi-Consistency Feature Matching with Non-Cooperative Games},
	author={Zhao, Chen and Yang, Jiaqi and Xiao, Yang and Cao, Zhiguo},
	booktitle={Proceedings of the IEEE International Conference on Image Processing},
	pages={1258--1262},
	year={2018},
	organization={IEEE}
}
```

# Usage
***
```
Run: Gird-GTM.exe “file_path“  “img_l” “img_r”

```
``file_path``: the path of the images.  
``img_l``: the name of the left image.  
``img_r``: the name of the right image.  

# Dataset
***
``1affine.txt``: affine informations around key-points in the left image.  
``1des.txt``: descriptors in the left image.  
``1key_location.txt``: positions of key-points in the left images, where the first line is the number of key-points.  
``2affine.txt``: affine informations around key-points in the right image.  2des.txt”: descriptors in the right image.    
``2key_location.txt``: positions of key-points in the right images, where the first line is the number of key-points.    
``match_idx.txt``: key-point indexes of matching pairs.  
``gt_location.txt``: positions of ground-truth inliers, where the first line is the number of inliers.  
