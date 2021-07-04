# Denoise_JPG_compression_Neural_Network

This project is image denoising and JPG image compression using neural network.

Dataset ==> 1750 images JPG format ==> 70% Train ==> 15% valid==> 15% test

For Image Denoising Preparation: 
  Images were added gussian filter of range approx 0.9
  
For Jpeg Compression preparation:
  Images were compression by approx 60% and add noise using gussian noise to 0.9 

# Image denoising and Jpeg Compression Neural Network :
U-net model,

Encoder :
5 blocks of Conv2d; => per block ==> Conv2d + leakrelu => dropout => batch normalisation


middle layer connecting Encoder => decoder : Conv2d

decoder :
5 Blocks of :
concat:  conv2d with deconv2d
Conv2d for concat layer
block of con2dTranspose ; => per block ==> Conv2dTranspose + leakrelu => dropout => batch normalisation



# Evaluation of test results for Image denoise :
Average PSNR: 



# Evaluation of test results for Jpeg Compression :
Average PSNR: 

All other supporting resources are located in this temporary G drive : https://drive.google.com/drive/folders/1TrSTo04FAsOLXYMVI5kfMyx2ZcvctYGo?usp=sharing
