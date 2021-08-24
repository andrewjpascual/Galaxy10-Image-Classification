# Galaxy10 Image Classification
Practice transfer learning on galaxy classification models to try and predict already labeled galaxies. This is using the Galaxy 10 dataset  
   
Galaxy10 is a dataset contains 21785, 69x69 pixels colored galaxy images (g, r and i band) separated in 10 classes. Galaxy10 images come from Sloan Digital Sky Survey and labels come from Galaxy Zoo. The dataset has columns: images with shape (25753, 69, 69, 3), ans, ra, dec, redshift, and pxscale (unit of arcsecond per pixel)  
  
Models included:  
- CNN without TL
- VGG 16
- VGG 19
- ResNet50

Collaborated with: Savanna Guertin

## Why did you build this?
 I felt this would be an interesting project in order to test different types of neural network models and compare their results. During the project we wanted to compare a CNN model without transfer learning, VGG 16, VGG 19, and ResNet50. Moreover, we wanted to contribute to the issue of tedious manual galaxy recognition by using machine learning these machine learning models.
 
## What did you learn from this?
During the testing we found that the models with transfer learning (VGG 16, VGG 19, and ResNet50) performed much better than the base CNN model without transfer learning. Additionally, the best model when comparing the four came to be the VGG 16 model with transfer learning.

## Comparing the F1-Scores of the four models used
![CIFAR-10 Screenshot1](https://user-images.githubusercontent.com/57194224/130534357-b8d31a1b-1279-4fce-a4a5-b3772560de21.png)

## Further examining the results for the best model (VGG 16)
![CIFAR-10 Screenshot2](https://user-images.githubusercontent.com/57194224/130534419-9ebd8c1b-aaa2-4a2c-b6c9-2a3322f118c8.png)

