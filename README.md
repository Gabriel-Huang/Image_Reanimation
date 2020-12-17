# Image-Reanimation

### This is a fun project I created for generating GIFs from single image inputs.

## Preliminary Results:
The network is trained on 7 clips of different subjects waving their hands for 100 epochs (5 min training time)

#### Input Image (First Frame)
![alt text](../master/results/frame_1.png)

#### GAN generated sequence (auto-regressive)
![alt text](../master/results/original.gif)


#### GAN generated sequence (auto-regressive with noise reduction)
![alt text](../master/results/nosie_reduction.gif)

#### GAN generated sequence with transform mask (background detials well preserved but noisy images)
![alt text](../master/results/trans_map.gif)

#### GAN generated sequence with anchor img (background detials well preserved but blurry animation)
![alt text](../master/results/anchor.gif)

#### Using Complementary Mask (Looking Good!)
![alt text](../master/results/complementary_mask.gif)

#### New Results on Making People Smile :)
![alt text](../master/results/UTDAL_04654v213.gif)  ![alt text](../master/results/UTDAL_04651v2131.gif)
