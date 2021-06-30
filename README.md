# Pretrained-I3D-for-Video-Emotion-Prediction
## Video Preprocessing
  * All video frames must be the same size, number and channel.
  * In this research, RGB channel and 32 frames for 30sec video are used for 3D convolutional network.


## Transfer Learning
### What it is?
 A transformation process of any learned knowledge from one or more source domain to a target domain
### Advantage
 * Reduction training time
 * Solving data scarcity problem
### How to do?
 * Fine-Tuning(Solving data scarcity problem)
### In my project
 * I use transfer learning to overcome the lack of data
 * A pre-trained 2D Music CNN trained with Million song dataset.
 
![image](https://user-images.githubusercontent.com/67357059/123909358-dde3cf80-d9b3-11eb-97d9-a5d1d733d5e0.png)
## Result
![image](https://user-images.githubusercontent.com/67357059/123909424-ffdd5200-d9b3-11eb-92e4-8776a084fd20.png)
![image](https://user-images.githubusercontent.com/67357059/123909469-0d92d780-d9b4-11eb-929e-7edd5d5823a5.png)
## Reference
1. Yagya Raj Pandeya (2020) Deep learning based late fusion of multimodal information for emotion classification of music video. Springer 
2. Bahuleyan H (2018) Music genre classification using machine learning techniques.
3. Choi K, Fazekas G, Sandler M and Cho K (2017) Transfer learning for music classification and regression tasks. International Society for Music Information Retrieval Conference
4. Dai W, Dai C, Qu S, Li J, and Das S (2016) Very deep convolutional neural networks for raw waveforms.
5. Grekow J (2018) From content-based music emotion recognition to emotion maps of musical pieces. Springer
