# Image_Segmentation

Normalized Cut is a classical way of Image Segmentation. 
Which uses Similarity Matrix which can be based on several factors used for segmentation like Intensity, Distance, Texture, Colour.
here i have done two kind of implementation first implementation is based on Intensity only and second is based on  Intensity and Distance both.
also effect of rotation and addition of gaussian noise on segmentation is visualized using Matplotlib.

Sample Image:
![test2](https://user-images.githubusercontent.com/111170719/218098958-45593512-cbcc-42c8-b98d-d2b0102c07a4.jpg)


nCut Output(based on Intensity difference only:
![test2_intensity var(int) =10](https://user-images.githubusercontent.com/111170719/218099022-6be78299-bd4c-4748-98d9-cea9ef8cc88f.jpg)

nCut Output(based on Intensity difference and Distance both:

![test2_both var(int) =10, var(dist) = 5 th=150](https://user-images.githubusercontent.com/111170719/218099116-ebd7fd7a-0dc3-49a2-9f1b-0ef378dd5de2.jpg)

Observation: Incorporating distance along with Intensity difference of the pixels helps in segmentation of individual object as whole.
in the example shown, we observe that eye are seperated as another segment when performing nCut using intensity difference only. but when used along with distance similarity eyes and baby is segmented as a single entity which is desirable.

Output:
Original Image Segmentation, Effect of Rotation , Effect of Gaussian Noise addition:
![1  test2](https://user-images.githubusercontent.com/111170719/218099926-74521766-168f-444c-ba97-7651232259a4.jpg)
