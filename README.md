# miccai17-mmwhs-hybrid
Thanks the great effort from Prof. Zhuang Xiahai in organizing the MMWHS Whole Heart Segmentation Challenge 2017.
Please cite this paper if the code contributes to your work:
"Hybrid Loss Guided Convolutional Networks for Whole Heart Parsing"
https://www.researchgate.net/publication/319702011_Hybrid_Loss_Guided_Convolutional_Networks_for_Whole_Heart_Parsing

you can find the required model below:

C3D Model:
https://drive.google.com/open?id=1N4LVb03Ehot34Bxcm1KkO14csuThOXUv
If you don't need this model, you can just comment the initialization of this model in code.

Trained model for CT segmentation:
https://drive.google.com/open?id=1Nly8ghHvedVC3EZetFJRRtLq7Ll-U0Fx

A CT data from the training dataset for demo:
https://drive.google.com/open?id=1b2sFaKrBfTRx6i0lBD5L6IZXP01W9L5C


If our work is helpful to you, please kindly cite our paper as:\\
@inproceedings{yang2017hybrid,\\
  title={Hybrid Loss Guided Convolutional Networks for Whole Heart Parsing},\\
  author={Yang, Xin and Bian, Cheng and Yu, Lequan and Ni, Dong and Heng, Pheng-Ann},
  booktitle={International Workshop on Statistical Atlases and Computational Models of the Heart},
  pages={215--223},
  year={2017},
  organization={Springer}
}



Segmentation Framework
![image](https://github.com/xy0806/miccai17-mmwhs-hybrid/blob/master/framework.png)

Probability Maps Generated by Different Loss Functions
![image](https://github.com/xy0806/miccai17-mmwhs-hybrid/blob/master/dice_entropy_maps.png)

Segmentation Results on CT and MR Volumes
![image](https://github.com/xy0806/miccai17-mmwhs-hybrid/blob/master/seg_results_a.png)
![image](https://github.com/xy0806/miccai17-mmwhs-hybrid/blob/master/seg_results.png)
