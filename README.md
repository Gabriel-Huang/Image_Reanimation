# image-reanimation

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

#### Newest Results Using Complementary Mask (Looking Good!)
![alt text](../master/results/complementary\mask.gif)
