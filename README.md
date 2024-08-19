# TalkingFace_Motion
![pipeline](https://github.com/user-attachments/assets/9874b985-1b8f-49dd-b2b7-7ba43fe654db)
This paper proposes a method to improve the quality of talking videos by enhancing the motion features learning ability, which effectively captures the dynamic changes and spatial-temporal relationships between head pose and facial motion.
It includes cross representation augmentation (CRA) and spatial-temporal alignment correction (STAC). CRA achieves feature augmentation by cross-processing motion features, which can better represent the temporal distribution of dynamic feature changes to improve the accuracy of motion features representation. STAC emphasizes the spatial-temporal alignment of motion features, ensuring the consistency of head pose and facial motion under different spatial-temporal conditions, thereby reducing the alignment loss of motion features. Extensive experiments have shown that the proposed method can accurately learn the motion features of a speaker in the reference video with natural video generation, which has better performance than other state-of-the-art methods.

## **Demo**
https://github.com/user-attachments/assets/fd22ecb9-256a-450b-8f56-6a01d34fd29a

## **Highlights**
-  A cross representation augmentation scheme namely CRA, is adopted to achieve feature augmentation by cross-processing of motion features, thereby improving the accuracy of feature representation. This is conducive to accurately learning motion features of reference videos and improving the accuracy of head pose and facial motion in generated videos.
-  A spatial-temporal alignment correction scheme namely STAC, is used to reduce the loss of feature alignment by achieving consistent spatial-temporal mapping of head pose and facial motion under different spatial-temporal conditions. This can reduce frame jitter or facial distortion in the generated videos, helping to achieve natural visual effect.

## **Installation**
-  We train and test based on Python 3.8
-  ffmpeg: ```sudo apt-get install ffmpeg```
-  To install the dependencies run: ```conda env create -f environment.yml```


## **Contact**
Our code is for research purposes only. More details will be released shortly. If you have any questions, please contact us: dongbiao@bit.edu.cn
