# Image-Caption-Generator-using-ResNet50-and-LSTM-model

## INTRODUCTION
“An image says alot more than words” is true for humans but when we talk about computers, telling what an image is representing seems inconceivable. 
Humans can deduce not just one, but a number of descriptions for just a single image and until the coming up of deep neural networks, this was not practical 
for a computer. But with the recent development of Deep Neural Networks, availability of huge datasets and computer power, it is possible to generate captions 
for an image. This project involves the use of Computer Vision and Natural Language Processing. In this paper, we have tried to develop a model which can 
take an image as an input and output a sentence that can describe the things in that picture. The model uses the Flickr8 dataset for the training purpose. 
The components of the method we used are: Convolutional Neural Network (CNN), Recurrent Neural Network (RNN) and sentence generation. The image is captioned 
by recognizing the objects that appear in the input image, using automatic feature engineering. In this paper, we have tried to develop a model that can take an
image as input and output a sentence that can describe things in that picture. The model uses the Flickr8 dataset for training purpose. The components of the 
method we use are: Convolutional Neural Network (CNN), Recurrent Neural Network (RNN) and Sentence Generation. In this project, CNN is used to create a dense feature
vector. This dense vector, also called an embedding, is used as a feature input to other algorithms or networks. For an image caption model, it becomes a dense
representation of the embedding image and is used as the initial state of the LSTM. In this image caption model, we created the embedding of the image. This embedding
will be fed into an LSTM as the initial state. This becomes the first previous state of the language model, which affects the next predicted words.

