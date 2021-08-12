# Biomimetic-Design-of-EECD-Method-for-Challenging-Water-Scenes

## Abstract

The key challenge of unmanned aerial vehicles (UAV) to detect objects in complex
water scenes is how to efficiently enhance the performance of change detection (CD).
Here, a novel bionic computational method is proposed to improve overall metrics
by using retina, pecten structure and lateral inhibition mechanisms. These structures
and characteristics of eagle eyes make it easier for our model to detect camouflaged
foreground objects and ignore dynamic background variations. Then, we proposed
an efficient cloning method and generate a synthetic multi-challenge dataset from real
world, named “WSCD”, with automatic accurate annotations at pixel-level. Besides,
we conduct experiments by using WSCD in combination with publicly available real
water datasets for algorithm evaluation. Through an extensive set of experiments, the
results indicate that: 1) the eagle eye-based change detection (EECD) model responds
strongly to object information and suppresses ripple or glare effects interference, which
helps it to perform best in real or synthetic water scenes. 2) synthetic dataset can
be used to quantitatively analyze and test different change detection models, where
illumination and waves still affect the performance of tradition vision systems.

## Description
Considering that change detection models have to deal with some challenges in water scenes, we generate various simulated multi-challenge sequences, 
including Basic, Dynamic Background, Illumination Variations. Note: Each specific sequence is also affected by other challenges, but one challenge is dominant.
This synthetic dataset is a photo-realistic vision laboratory that validates the performance of different methods.

## The overall framework of the proposed EECD method
![image](https://github.com/PC-Lab-Virtual-Reality/Biomimetic-Design-of-EECD-Method-for-Challenging-Water-Scenes/blob/main/Figure/fig1.jpg)

## Examples of the real and synthetic dataset
![image](https://github.com/PC-Lab-Virtual-Reality/Biomimetic-Design-of-EECD-Method-for-Challenging-Water-Scenes/blob/main/Figure/fig2.jpg)


## Download
The WSCD is a water-scene dataset designed to design and evaluate a variety of computer vision models for change detection.
We provide one [.rar] archive per type of data as described below. Our indexes always start from 000001. In the following,

WSCD_dataset_rbg_2021: Each area is simply a folder in the format: The compressed file contains the original image.

[WSCD_dataset_rbg_2021.rar](https://drive.google.com/file/d/1aNI2fUiC0U3NZ_5XAv7qVwIdm2RHrhPX/view?usp=sharing)

WSCD_dataset_gt_2021: The compressed file contains the ground truth of object detection. The per-pixel segmentation ground truth is encoded as per-frame .png files (standard 8-bit precision per channel).

[WSCD_dataset_gt_2021.rar](https://drive.google.com/file/d/1eUqWA3AenOuF58kuySkImw9JeU8HZLoK/view?usp=sharing)

## Sample images of WSCD sequences
![image](https://github.com/PC-Lab-Virtual-Reality/Biomimetic-Design-of-EECD-Method-for-Challenging-Water-Scenes/blob/main/Figure/fig3.jpg)

## Examples of change detection results on WSCD using different models
![image](https://github.com/PC-Lab-Virtual-Reality/Biomimetic-Design-of-EECD-Method-for-Challenging-Water-Scenes/blob/main/Figure/fig4.jpg)

## Citations
All rights of the WSCD Dataset are reversed by the Peng Cheng Laboratory. It is free for academic research, and your cooperation with us is appreciated. Feel free to contact us if you have any questions.

If the Synthetic-Boat-Sequence Dataset is used in your research, please cite the following papers:

1. Xuan Li, Kunfeng Wang, Yonglin Tian, Lan Yan, Fang Deng, Fei-Yue Wang, "The ParallelEye Dataset: A Large Collection of Virtual Images for Traffic Vision Research," 
IEEE Transactions on Intelligent Transportation Systems, 2018, 20(6): 2072-2084. [Link](https://ieeexplore.ieee.org/document/8451919/)

2. Xuan Li, Yutong Wang, Lan Yan, Kunfeng Wang, Fang Deng, Fei-Yue Wang, "ParallelEye-CS: A New Dataset of Synthetic Images for Testing the Visual Intelligence of Intelligent Vehicles," IEEE Transactions on Vehicular Technology, 2019, 68(10): 9619-9631. [Link](https://ieeexplore.ieee.org/abstract/document/8807212)

3. Xuan Li, Kunfeng Wang, Xianfeng Gu, Fang Deng, Fei-Yue Wang, "ParallelEye Pipeline: An Effective Method to Synthesize Images for Improving the Visual
Intelligence of Intelligent Vehicles," IEEE Transactions on Systems Man Cybernetics-Systems.(accepted) 

