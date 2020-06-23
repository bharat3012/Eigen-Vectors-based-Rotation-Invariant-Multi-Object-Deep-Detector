# Eigen-Vectors-based-Rotation-Invariant-Multi-Object-Deep-Detector
Rotated object detection using YOLOv3-CNN Object Detector without training with augmented images.

## Abstract:

In this paper, we propose an accurate, scalable data-free approach based on eigenvectors and Convolutional Neural Networks (CNNs) for rotated object detection. Detecting an arbitrarily diverted object poses a challenging problem, as features extracted by CNNs are variant to small changes in shift and scale. They lack in performance for images at orientation different from input data. Hence, we introduce a novel two-step architecture, which detects multiple objects at any angle in an image efficiently. We utilize eigenvector analysis on the input image based on bright pixel distribution. The vertical and horizontal vectors are used as a reference to detect the deviation of an image from the original orientation. This analysis gives four orientations of the input image which, that pass through a pre-trained YOLOv3 with proposed decision criteria. Our approach referred to as "Eigen Vectors based Rotation Invariant Multi-Object Deep Detector" (EVRI-MODD), produces rotation invariant detection without any additional training on augmented data and also determines actual image orientation without any prior information. The proposed network achieves high performance on Pascal-VOC 2012 dataset. We evaluate our network performance on three differently rotated angles, 90°, 180°, and 270°, and achieves a significant gain in accuracy by 48%, 50%, and 47% respectively, over YOLOv3.

## Please Cite

1. BibTex
```
@INPROCEEDINGS{9070989,
  author={B. {Giddwani} and D. {Varma} and M. {Murali} and R. K. {Gorthi}},
  booktitle={2020 7th International Conference on Signal Processing and Integrated Networks (SPIN)}, 
  title={Eigen Vectors based Rotation Invariant Multi-Object Deep Detector}, 
  year={2020},
  volume={},
  number={},
  pages={246-251},}
```

2. Plain Text
```
B. Giddwani, D. Varma, M. Murali and R. K. Gorthi, "Eigen Vectors based Rotation Invariant Multi-Object Deep Detector,"
2020 7th International Conference on Signal Processing and Integrated Networks (SPIN), Noida, India, 2020,
pp. 246-251, doi: 10.1109/SPIN48934.2020.9070989.
```

## Link:
https://ieeexplore.ieee.org/abstract/document/9070989
