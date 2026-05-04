# Drone-Image-Semantic-Segmentation

A deep learning project that segments aerial/drone imagery into 4 land-cover classes — Road, Water, Green Land, and Background — using a custom U-Net architecture built with TensorFlow/Keras.

📌 Problem Statement :

Manually analyzing drone or satellite imagery for land-cover mapping is time-consuming and error-prone. This project automates that process using semantic segmentation — assigning a class label to every pixel in an image — enabling applications in urban planning, flood monitoring, and environmental analysis.


🗂️ Dataset

Source: Aerial drone tile images with corresponding RGB-coded segmentation masks
Structure: 9 tiles, each containing multiple image patches (256×256 px)
Total samples: ~72 images → expanded to 720+ samples via augmentation
Classes:

<img width="830" height="268" alt="image" src="https://github.com/user-attachments/assets/8da686b8-d492-48c9-b76e-430016034bc7" />

Training Results:

<img width="380" height="297" alt="image" src="https://github.com/user-attachments/assets/831e0cd5-938f-4318-aa5a-c01cb00eb2ea" />

Output:

<img width="1643" height="534" alt="image" src="https://github.com/user-attachments/assets/e0cea4dd-a779-4a8b-b4ef-81a6cc7ec32f" />
