# Combining Vision and Language:
## Creating an Image-Captioning Architecture using Deep Learning

Project Repo for the Image Captioning using Transformers project done for the Deep Learning class at BU.  
![Basic Architecture](https://raw.githubusercontent.com/yunjey/pytorch-tutorial/master/tutorials/03-advanced/image_captioning/png/model.png "Basic Architecture")  
This project aimed to explore different architectures which perform automated image captioning, and garner an understanding of how the different component networks work together to create the output caption. We explored image captioning models which work by combining an encoder module which computes a feature vector to represent input images, and a decoder module which uses these features to generate a caption describing the image content. Typically, the encoder is a Convolutional Neural Net (CNN) and the decoder is a Recurrent Neural Net (RNN). However, some features of transformer models suggested that they may perform as well or better than RNNs. Based on this intuition, we wrote and implemented a transformer in order to replace the decoder module. We compare the new model’s performance to that of the CNN+RNN image captioning architecture. In addition, we experiment with different CNN architectures in order to find the most optimal CNN networks to use.  

## Steps to run the project on the SCC-  
1. Login and reserve a gpu instance of Jupyter notebook with the dependencies - cuda/10.1 python3/3.7.7 pytorch/1.6.0. on the [SCC.](https://scc-ondemand2.bu.edu)  
2. Navigate to /projectnb/ec523/simonsai/  
3. This folder contains the dataset required to run this project, as well as the loss data, and the trained models in pickle form.  
4. Run all the cells besides the training loop in the notebook of the model you want to test, namely resnet.ipynb, vgg.ipynb or transformer.ipynb.  
5. The notebooks show the output and losses towards the end of the notebooks. The get_prediction() cell can be run a few times to obtain a series of different sample outputs and predictions.  
  
[Slides explaining the project](https://docs.google.com/presentation/d/1oyroor4uiwlbYHFFg0oXp_gjM9Grxvnv6VJa4GG6_dg/edit?usp=sharing)
