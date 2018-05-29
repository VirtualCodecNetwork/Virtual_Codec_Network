# From Auto-Encoder to Virtual Codec Supervised Re-Sampling Network for Image Compressionn (Submitted to IEEE TMM)
Author: Lijun Zhao, Huihui Bai, Anhong Wang, Yao Zhao

## Image Re-Sampling Compression Method
Our IRSC method can be not only used for deep neural networks based compression framework (DN2C), but it also can be applied to standard-compliant image compression framework (SCIC).
- Framework1
<p align='center'>  
  <img src='fig/DN2C.jpg' width='1000'/>

- Networks
<p align='center'>  
  <img src='fig/SCIC.jpg' width='1000'/>



## NOTICE
***IF you use our code, please cite our paper "From Auto-Encoder to Virtual Codec Supervised Re-Sampling Network for Image Compression"

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


## Demo using pre-trained model
   %%% Pre-trained MDCNN model can be downloaded at (put it in the folder 'tmp'):
   
   %%% Please change "data_path" and "log_directory" in "main_test.py" to be your path
   
   python main_test.py
