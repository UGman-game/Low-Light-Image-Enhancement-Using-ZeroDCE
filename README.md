# Low-Light-Image-Enhancement-Using-ZeroDCE

This project implements a Zero-Reference Deep Curve Estimation (ZeroDCE) network for enhancing low-light images. The model employs a Deep Convolutional Encoder (DCE) network to improve image illumination without requiring paired or unpaired training data, making it versatile for real-world applications.

## Key Features:

+ Data Loading and Preparation: Utilizes TensorFlow data pipelines to load and preprocess images from the LOL dataset, ensuring efficient data handling.

+ Model Architecture: Constructs a DCE network with 6 convolutional layers and multiple loss functions to enhance image quality.

+ Custom Loss Functions: Implements custom loss functions including color constancy, exposure, illumination smoothness, and spatial consistency loss to guide the network in producing natural-looking enhancements.

+ Training and Evaluation: Trains the model on a dataset of low-light images and evaluates its performance using Structural Similarity Index (SSIM) and Peak Signal-to-Noise Ratio (PSNR) metrics.

+ Inference and Visualization: Provides functions for inferring enhanced images from test data and visualizing the results alongside performance metrics.

+ Model Saving: Saves the trained model weights for future use and deployment.

## Results:
The model demonstrates significant improvements in image quality, achieving high SSIM and PSNR values, which are validated through rigorous testing and visualization.

![image](https://github.com/UGman-game/Low-Light-Image-Enhancement-Using-ZeroDCE/assets/57181653/b73b3caa-f391-480b-bde2-21b0f1c2adc3)
![image](https://github.com/UGman-game/Low-Light-Image-Enhancement-Using-ZeroDCE/assets/57181653/cfb96456-3334-4e90-b7e1-cb2d43f38894)

