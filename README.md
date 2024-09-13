## ASL-Classification-Using-CNN

# Introduction
This project delves into the realm of American Sign Language (ASL) Alphabet Classification using Convolutional Neural Networks (CNNs). ASL, a vital visual language within the Deaf and hard-of-hearing community, serves as a unique mode of communication. In computer vision and artificial intelligence, recognizing ASL gestures holds great significance. This endeavor's primary goal is to harness deep learning's capabilities, specifically CNNs, to build a model adept at precisely identifying and classifying the distinctive hand gestures that represent each letter of the English alphabet in ASL. This project demonstrates the prowess of advanced technologies and contributes to fostering communication and accessibility for the Deaf community. By exploring the complexities of image recognition, our work endeavors to bridge the gap between computer vision and the intricate nature of sign language. We anticipate that this project will positively impact the field of assistive technology, steering us toward a future that is more inclusive and accessible.

![image](https://github.com/user-attachments/assets/07da6432-2536-470e-b796-a5c9c7e21c97)

# Motivation using ASL dataset
The insights derived from hearing-related statistics underscore the importance of developing inclusive ASL recognition models. As we navigate through the prevalence of hearing loss and its diverse impact, the need for robust datasets and representative models becomes paramount. Additionally, our project aligns to address the usage gap in hearing aids, utilizing technology to enhance accessibility and communication for individuals facing hearing-related challenges.

![image](https://github.com/user-attachments/assets/f3809a9e-6fae-421b-8aed-345bbac438be)

# Data
We used data sets from two different sources.

Source 1: https://www.kaggle.com/datasets/grassknoted/asl-alphabet

Source 2: https://www.kaggle.com/code/sharmayashi/signlangdetection/input

First, we created a CNN model, we defined the layers for it.
after that we applied transfer learning using pre-built and pre-trained models with ImageNet weights. The primary objective of transfer learning is to leverage knowledge gained from a large dataset and apply it to a smaller one. We froze the early convolutional layers of the network, training only the last layers responsible for predictions. The concept is that the initial convolutional layers capture general, low-level features applicable across various images, such as edges, patterns, and gradients. The subsequent layers specialize in identifying specific features within individual images. Our choice of pre-trained models includes ResNet18, AlexNet, DenseNet, and VGG16, with an image size of 224x224, a batch size of 64/128, 10 epochs, and no data augmentation.

# results
![image](https://github.com/user-attachments/assets/aacb556c-e78e-468c-a9c6-5c4e684e0f8d)
