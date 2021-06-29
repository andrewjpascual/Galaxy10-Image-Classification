# Galaxy10 Image Classification
Practice transfer learning on galaxy classification models to try and predict already labeled galaxies. This is using the Galaxy 10 dataset  
   
Galaxy10 is a dataset contains 21785, 69x69 pixels colored galaxy images (g, r and i band) separated in 10 classes. Galaxy10 images come from Sloan Digital Sky Survey and labels come from Galaxy Zoo. The dataset has columns: images with shape (25753, 69, 69, 3), ans, ra, dec, redshift, and pxscale (unit of arcsecond per pixel)  
  
Models included:  
- CNN without TL
- VGG 16
- VGG 19
- ResNet50
