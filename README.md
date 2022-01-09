# image-super-resolution-using-deep-learning-CNN-and-PSNR

This project is delivered as part of my Masters in Big Data Science (MSc BDS) Program internal training for the module named “Deep Learning and Computer Vision” in Queen Mary University of London (QMUL), London, United Kingdom.  

This project aims to obtain practical knowledge and hands-on understanding of the concepts of image super-resolution, deep learning using convolutional neural networks (CNN) and peak signal-to-noise ratio (PSNR).   

The project addresses 3 different problem statements and use cases; with the solutions implemented using Python and its module named PyTorch.

Problem Statement 1: Understanding Image Super-Resolution
 
Questions Answered: 
1. What are the concepts of image size and image resolution? 
2. What is gray-scale or single-channel image super-resolution? 
3. What is Ground Truth image? 
4. How to measure the quality of the output high-resolution images? 

Sub-Tasks Addressed:
1. To read the image named butterfly_GT.bmp 
2. To show the size of this image 
3. To convert the image from the RGB colour space into the gray-scale space
4. To shrink the current image by 3 times with bicubic interpolation algorithm
5. To enlarge the current image by 3 times with bicubic interpolation algorithm 

Problem Statement 2: Understanding Deep Learning by Convolutional Neural Network (CNN)

Questions Answered: 
What are the parameters of a CNN? 
2. What is the target of CNN model training? 
3. What is the actual behaviour in testing stage with a CNN? 
4. What is feature map? 
5. How to perform convolution filtering? 

Sub-Tasks Addressed:
1. To load the pre-trained model named model. pth 
2. To set and show the weights of the first convolutional layer
	a. To set the channel number of the input 
	b. To set the filter number 
	c. To set the filter size 
	d. To set the padding 
	e. To show the value of the 1st filter in command window 
	f. To show the bias of the 10th filter in command window
3.  To set and show the weights of the second convolutional layer
	a. To set the channel number of the input 
	b. To set the filter number 
	c. To set the filter size 
	d. To set the padding 
	e. To show the value of the 5th filter in command window 
	f. To show the bias of the 6th filter in command window
4. To set show the weights of the third convolutional layer
	a. To set the filter number 
	b. To set the filter size 
	c. To set the padding 
	d. To show the value of the 1st filter in command window 
	e. To show the bias of the 1st filter in command window 
5. To perform 2-d convolution filtering on a 2-d matrix with a given filter 


Problem Statement 3: Image Super-Resolution using Deep Convolutional Network

Questions Answered: 
1. How to use a trained SRCNN to perform image super-resolution (testing stage)? 
2. What are the input and the output of SRCNN? 
3. How to conduct qualitative and quantitative comparison between two different methods? 
4. What is the typical numerical measure metric for quantitative analysis? 
5. What is the maximum power of imaging signal (i.e. pixel) and noise signal, e.g. image of uint8 type? 
	
Sub-Tasks Addressed:
1. To get and show the Ground Truth image 
2. To get and show the low-resolution image 
3. To get the input image into the SRCNN 
4. To call SRCNN to super-resolve the input image 
5. To get and show the output high-resolution image by SRCNN 
6. To compute the PSNR of the high-resolution image against the Ground Truth image 
7. To get the high-resolution image with bicubic interpolation algorithm (baseline result) 
8. To compute the PSNR of the baseline result 
9. To compare the results of the two methods in terms of PSNR 

NOTE: Due to the data privacy and the data protection policy to be adhered by the students; the datasets and the solution related code are not exposed and updated in the GitHub public profile; in order to be compliant with the Queen Mary University of London (QMUL) policies.

