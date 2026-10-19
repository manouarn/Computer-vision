# Lab 2 — R-CNN Family, Step by Step

Run `Lab_02_R_CNN_Family_Step_by_Step.ipynb` from top to bottom in Jupyter or Google Colab.

## Install

Use a matching `torch` / `torchvision` installation from https://pytorch.org/get-started/locally/ then:

```bash
pip install numpy matplotlib pillow scikit-image opencv-contrib-python jupyter
```

First run downloads pretrained MobileNet, Faster R-CNN, and Mask R-CNN weights. GPU is recommended for full detection stages, but CPU is supported. Ensure Internet access and adequate memory. No training is performed. Steps 2–3 demonstrate core architectural ideas, not full R-CNN/Fast R-CNN detector implementations.

## Contents
1. Environment and images
2. Selective Search proposals
3. Original R-CNN feature extraction
4. Fast R-CNN shared features and RoI Pooling
5. Faster R-CNN RPN and predictions
6. Mask R-CNN RoIAlign and masks
7. Checkpoints and report questions

## References
- https://docs.opencv.org/4.x/d5/df0/group__ximgproc__segmentation.html
- https://docs.pytorch.org/vision/stable/models.html#object-detection-instance-segmentation-and-person-keypoint-detection
