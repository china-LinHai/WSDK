# Epipolar Constraint Guided Differentiable Keypoint Detection and Description

Sparse local feature matching methods have made significant strides in a variety of visual geometric tasks. Recently, the weakly supervised  under epipolar constraint approaches achieve stronger performance compared to the fully supervised methods through the decoupled training describe-then-detect. However, such methods base on the policy gradient to train the detector, ignoring the reliability of the keypoints. Meanwhile, many of the sparse local feature matching methods place more emphasis on accuracy over speed, being unfriendly for real-time applications. To address these issues, we introduce the differentiable keypoint extraction and the dispersity peak loss to generate clean score maps and enhance the reliability of the keypoints in the weakly supervised method. Additionally, we propose a straightforward yet efficient model that achieves a good balance between accuracy and speed. We conduct experiments on multiple public benchmark datasets, achieving higher performance than existing methods. 

![image](https://github.com/FYL0123/WSDK/blob/main/imgs/gflops_mma.png)

# Training
Download the preprocessed subset of MegaDepth from CAPS: https://github.com/qianqianwang68/caps
