# TalkingFace_Motion
![pipeline06](https://github.com/user-attachments/assets/2c296b05-fa54-4b40-bfb6-f8d0c81ff12b)
This paper proposes a method to improve the quality of talking videos by enhancing the motion features learning ability, which effectively captures the dynamic changes and spatial-temporal relationships between head pose and facial motion.
It includes cross representation augmentation (CRA) and spatial-temporal alignment correction (STAC). CRA achieves feature augmentation by cross-processing motion features, which can better represent the temporal distribution of dynamic feature changes to improve the accuracy of motion features representation. STAC emphasizes the spatial-temporal alignment of motion features, ensuring the consistency of head pose and facial motion under different spatial-temporal conditions, thereby reducing the alignment loss of motion features. Extensive experiments have shown that the proposed method can accurately learn the motion features of a speaker in the reference video with natural video generation, which has better performance than other state-of-the-art methods.

## **Demo**
https://github.com/user-attachments/assets/fd22ecb9-256a-450b-8f56-6a01d34fd29a

## **Dataset**
Our datasets come from public interviews or TV shows.
-  https://github.com/user-attachments/assets/fce47b5a-e4ab-4e6c-8005-623dc2bc9c27
-  https://github.com/user-attachments/assets/f2b57226-1595-4b00-8a00-eb0d53dd229b
-  https://github.com/user-attachments/assets/59eb8c2a-92f6-4a2e-a1fc-6c97334f1b46
-  https://github.com/user-attachments/assets/501ce30e-ab4c-4b55-b98b-9a8767178e49
-  https://github.com/user-attachments/assets/50486245-fe6a-451f-a201-837bb8f2386c

## **Highlights**
-  A cross representation augmentation scheme namely CRA, is adopted to achieve feature augmentation by cross-processing of motion features, thereby improving the accuracy of feature representation. This is conducive to accurately learning motion features of reference videos and improving the accuracy of head pose and facial motion in generated videos.
-  A spatial-temporal alignment correction scheme namely STAC, is used to reduce the loss of feature alignment by achieving consistent spatial-temporal mapping of head pose and facial motion under different spatial-temporal conditions. This can reduce frame jitter or facial distortion in the generated videos, helping to achieve natural visual effect.

## **Installation**
-  We train and test based on Python 3.8
-  ffmpeg: ```sudo apt-get install ffmpeg```
-  To install the dependencies run: ```conda env create -f environment.yml```


## **Contact**
Our code is for research purposes only. More details will be released shortly. If you have any questions, please contact us: dongbiao@bit.edu.cn
