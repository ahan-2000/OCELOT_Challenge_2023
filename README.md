# OCELOT Challenge 2023
This repo is being used to develop the codebase for the OCELET-2023 as a part of the Grand Challenge.

Machine learning algorithms play a crucial role in cancer cell classification from histopathological images, as they can analyze vast amounts of data and identify subtle patterns that might elude human detection. Their ability to accurately distinguish between normal and cancerous cells has the potential to improve early diagnosis, treatment planning, and ultimately enhance patient outcomes in cancer care. In this paper, we introduce a deep-learning algorithm for simultaneous cancer cell detection and semantic segmentation of histopathological images. Our proposed method has shown promising performance on the recent OCELOT challenge.  

Models Used: 
1. UNet based on InceptionV3 Encoders
2. UNet based on EfficientNetB2 Encoders



|               Model Name              | IoU Score |
| --------------------------------------| --------- | 
| InceptionV3 Based Encoder U-Net	      | 0.47292   | 
| EfficientNetB2 Based Encoder U-Net    | 0.6514    | 


Training Curves for EfficientNetB2

![Training Curves for EfficientNetB2](https://github.com/ahan-2000/OCELOT_Challenge_2023/blob/main/Images/download.png)
![Training Curves for EfficientNetB2](https://github.com/ahan-2000/OCELOT_Challenge_2023/blob/main/Images/download3.png)

Training Curves for InceptionV3

![Training Curves for InceptionV3](https://github.com/ahan-2000/OCELOT_Challenge_2023/blob/main/Images/download1.png)
![Training Curves for InceptionV3](https://github.com/ahan-2000/OCELOT_Challenge_2023/blob/main/Images/download2.png)

Prediction Image 1:

![Prediction Images](https://github.com/ahan-2000/OCELOT_Challenge_2023/blob/main/Images/pred1.png)

Prediction Image 2:

![Prediction Images](https://github.com/ahan-2000/OCELOT_Challenge_2023/blob/main/Images/pred2.png)

Prediction Image 3:

![Prediction Images](https://github.com/ahan-2000/OCELOT_Challenge_2023/blob/main/Images/pred3.png)




