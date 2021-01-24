# Densely Deformable Efficient Salient Object Detection Network

### Contents
1. Introduction
2. The proposed DDNet
3. Requirements and how to run?
4. Our SOD dataset (S-SOD)
4. Visual results and comparisons
5. Citation and acknowledgements

## Introduction
In this paper, inspired by the best background=foreground separation abilities of deformable convolutions, we employ them in our Densely Deformable Network
(DDNet) to achieve efficient SOD. The salient regions from densely deformable convolutions are further refined using transposed convolutions to optimally generate the saliency maps. Quantitative and qualitative evaluations using the recent SOD dataset against 22 competing techniques show our method’s efficiency and effectiveness.

## The proposed DDNet
The proposed DDNet uses three main blocks to generate optimal saliency. Firstly, two dense convolution blocks represent lowlevel features of the input RGB images. Then we propose densely connected deformable convolutions to learn effective features of salient regions and their corresponding boundaries. Finally, we employ transpose convolution and upsampling to generate the resultant saliency image, refer to the figure below:

![The proposed DDNet schematic diagram](https://github.com/tanveer-hussain/EfficientSOD/blob/main/Figures/Framework-V1.png)

## Requirements and how to run?

## Our SOD dataset (S-SOD)

## Visual comparisons
![Visual results on challenging SIP test images](https://github.com/tanveer-hussain/EfficientSOD/blob/main/Figures/DDNetResults.png)

## Citation and acknowledgements

