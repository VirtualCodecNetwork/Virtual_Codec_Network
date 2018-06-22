# Virtual Codec Supervised Re-Sampling Network for Image Compression
Author: Lijun Zhao, Huihui Bai, Anhong Wang, Yao Zhao

## Image Re-Sampling Compression Method
Our IRSC method can be not only used for deep neural networks based compression framework (DNNC), but it also can be applied to standard-compliant image compression framework (SCIC).
- DNNC Framework
<p align='center'>  
  <img src='fig/DN2C.jpg' width='300'/>

- SCIC Framework
<p align='center'>  
  <img src='fig/SCIC.jpg' width='1000'/>



## NOTICE
***IF you use our code, please cite our paper "Virtual Codec Supervised Re-Sampling Network for Image Compression" and "Learning a Virtual Codec Based on Deep Convolutional Neural Network to Compress Image"

## Prerequisites:
1. Linux
2. Python 2
3. tensorflow version 1.0 and other dependencies such as numpy, argparse, cv2
3. CPU or NVIDIA GPU + CUDA CuDNN


## Installation:
1. Install tensorflow-1.0

2. Install python package: numpy, argparse, cv2

3. git clone https://github.com/VirtualCodecNetwork/Virtual_Codec_Network/    
   
   cd Virtual_Codec_Network 
   
## Training Dataset, Validation Dataset, and Testing Dataset
   They can be downloaded at https://www.dropbox.com/sh/p9s8y686w6wdkj4/AADhvSQdOGsUSi14dLnQ6WDxa?dl=0

## Demo using pre-trained model
   %%% Pre-trained model can be downloaded at (put it in the folder 'tmp'):
   
   %%% Please change "data_path" and "log_directory" in "main_test.py" to be your path
   
   python main_test.py
