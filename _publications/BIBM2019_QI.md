---
title: "BIBM2019: Semi-Supervised Attention-Guided CycleGAN for Data Augmentation on Medical Images"
collection: publications
permalink: /publication/BIBM2019_QI
excerpt: '
**Authors** :  **Zhenghua Xu**, Chang Qi and Guizhi Xu


**Place** : San Diego, USA


**Date** : November 18 – November 21, 2019
'
date: 2019-11-18
venue: '2019 IEEE International Conference on Bioinformatics and Biomedicine (IEEE BIBM 2019), (CCF Rank B, Acceptance rate: 18%)'

---
**Authors:** **Zhenghua Xu**, Chang Qi and Guizhi Xu  
**Abstract:** Recently, deep learning methods, in particular, convolutional neural networks (CNNs), have made a massive breakthrough in computer vision. And a big amount of annotated data is the essential cornerstone to reach this success.
However, in the medical domain, it is usually difficult (and sometimes even impossible) to get sufficient data for some specific learning tasks. Consequently, in this work, a novel data augmentation solution, called semi-supervised attention-guided CycleGAN (SSA-CycleGAN) is proposed to resolve this problem. Specifically, a cycle-consistency GANs-based model is first proposed to generate synthetic tumor (resp., normal) images from normal (resp., tumor) images. Then, a semi-supervised attention module is further proposed to enhance the model's capability in learning the important details of the training images, which in turns help the generated synthetic images become more realistic. To verify its effectiveness, experimental studies are conducted on three medical image datasets with limited amounts of MRI images, and the proposed SSA-CycleGAN is applied to generate synthetic tumor and normal MRI images for data augmentation. Experimental results show that i) SSA-CycleGAN can add (resp., remove) tumor lesions on (resp., from) the original normal (resp., tumor) images and generate very realistic synthetic tumor (resp. normal) images; and ii) in the ResNet18-based MRI image classification tasks based on these datasets, data augmentation using SSA-CycleGAN achieves much better classification performances than the classic data augmentation methods.

[[Download paper here]](http://zhx-hebut.github.io/files/BIBM2019QI.pdf)
