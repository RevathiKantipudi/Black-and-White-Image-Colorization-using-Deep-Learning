Black and White Image Colorization Using Convolutional Neural Networks

Overview:
Colorization of black and white images has become increasingly important with the advent of high-quality and high-resolution pictures in modern-day life. This project proposes a method for converting black and white pictures to color pictures. This project is mainly designed for coloring black and white images using the Deep learning Algorithms like CNN (Convolutional Neural Networks).

Dataset:
An image dataset called MIRFLICKR25k is used to train the model for image colorization. The images consist of different random images of humans, objects, places, things, animals.

Link: https://www.kaggle.com/datasets/shravankumar9892/image-colorization

Model Architecture:
A convolutional neural network (CNN) architecture for black and white image colorization is built with regularization techniques such as dropout and L2 regularizer to prevent overfitting. Then the built network is then trained by using Adam optimizer which has a suitable learning rate. During training, the network weights are updated iteratively to reduce the MSE or the loss between predicted and original color images. Then the trained network is then tested on a different testing dataset to understand and evaluate the performance using metrics such as MSE, Loss, PSNR.

We also tried other deep learning architectures such as Encoder Decoder and Auto Encoder with different datasets.

Other dataset links:
https://www.kaggle.com/datasets/theblackmamba31/landscape-image-colorization

https://www.kaggle.com/datasets/thedownhill/art-images-drawings-painting-sculpture-engraving

Deployment:
This project includes a web interface for black and white image colorization using Streamlit. Upload black and white images to visualize their colorized versions.