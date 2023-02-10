# Image Segmentation (Using Normalized Cut)

Normalized Cut is a classical way of Image Segmentation. 
Which uses Similarity Matrix which can be based on several factors used for segmentation like Intensity, Distance, Texture, Colour.
here i have done two kind of implementation first implementation is based on Intensity only and second is based on  Intensity and Distance both.
also effect of rotation and addition of gaussian noise on segmentation is visualized using Matplotlib.

## Sample Image:
<h1 align="center">
  
![test2](https://user-images.githubusercontent.com/111170719/218098958-45593512-cbcc-42c8-b98d-d2b0102c07a4.jpg)

  </h1>

## Normalized Cut Output Comparision:
<h1 align="center">
<img width="808" alt="Screenshot 2023-02-10 185717" src="https://user-images.githubusercontent.com/111170719/218103559-d0350807-9cd6-4a28-b13b-713d82159c69.png">

  </h1>
  
Incorporating distance along with Intensity difference of the pixels helps in segmentation of individual object as whole.
in the example shown, we observe that eye are seperated as another segment when performing nCut using intensity difference only. but when used along with distance similarity eyes and baby is segmented as a single entity which is desirable.

## Output(Original Image Segmentation, Effect of Rotation , Effect of Gaussian Noise addition):


  ![1  test2](https://user-images.githubusercontent.com/111170719/218099926-74521766-168f-444c-ba97-7651232259a4.jpg)
