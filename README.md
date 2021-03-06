# Pretrained-I3D-for-Video-Emotion-Prediction
## Data
 * 30 sec video with 6 classification label
## Video Preprocessing
  * All video frames must be the same size, number and channel.
  * In this research, RGB channel and 32 frames for 30sec video are used for 3D convolutional network.

![image](https://user-images.githubusercontent.com/67357059/123912142-9fe8aa80-d9b7-11eb-8ef5-25cb63009e8b.png)

## I3D Network
 * I use I3D Network pretrained kinetic dataset.
### Inflating
 * The method of replacing N x N filters with N x N x N filters.
 * In detail, increase the dimension of the filter and divide the weight by 1/N.

 ![image](https://user-images.githubusercontent.com/67357059/123912383-ee964480-d9b7-11eb-8465-59bdd2d28a10.png)
 

## Result
![image](https://user-images.githubusercontent.com/67357059/123912463-066dc880-d9b8-11eb-9081-e0c8cdab914c.png)
![image](https://user-images.githubusercontent.com/67357059/123912486-0f5e9a00-d9b8-11eb-98e9-d4ae53481abe.png)

## Reference
1. Yagya Raj Pandeya (2020) Deep learning based late fusion of multimodal information for emotion classification of music video. Springer 
2. Quo vadis, action recognition? A new model and the kinetics dataset.
3. Fan Y, Lu X, Li D, Liu Y (2016) Video-based emotion recognition using CNN-RNN and C3D hybridnetworks. International conference on multimodal interfaces. Tokyo, Japan
