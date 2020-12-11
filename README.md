# Combining Vision and Language:
## Creating an Image-Captioning Architecture using Deep Learning

Project Repo for the Image Captioning using Transformers project done for the Deep Learning class at BU.  
![Basic Architecture](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.analyticsvidhya.com%2Fblog%2F2018%2F04%2Fsolving-an-image-captioning-task-using-deep-learning%2F&psig=AOvVaw3UtKyO3XOBQBoDFcQ1TNlw&ust=1607732184457000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCIDtuJ_TxO0CFQAAAAAdAAAAABAD)
This project aimed to explore different architectures which perform automated image captioning, and garner an understanding of how the different component networks work together to create the output caption. We explored image captioning models which work by combining an encoder module which computes a feature vector to represent input images, and a decoder module which uses these features to generate a caption describing the image content. Typically, the encoder is a Convolutional Neural Net (CNN) and the decoder is a Recurrent Neural Net (RNN). However, some features of transformer models suggested that they may perform as well or better than RNNs. Based on this intuition, we wrote and implemented a transformer in order to replace the decoder module. We compare the new model’s performance to that of the CNN+RNN image captioning architecture. In addition, we experiment with different CNN architectures in order to find the most optimal CNN networks to use.  

[Slides explaining the project](https://docs.google.com/presentation/d/1oyroor4uiwlbYHFFg0oXp_gjM9Grxvnv6VJa4GG6_dg/edit?usp=sharing)
