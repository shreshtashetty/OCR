# Optical Character Recognition (OCR)
OCR entails recognizing actual characters of a word from a picture of the word.
The network used therefore has convolutional layers as its initial layers which process the image to give feature maps, and bidirectional LSTMs as its layer layers which process these feature maps to give actual letters.
The loss used is a [Connectionist Temporal Classification (CTC)](https://distill.pub/2017/ctc/) loss, which has been implemented as a separate layer.
##
This repo is an implementation of the paper: An End-to-End Trainable Neural Network for Image-based Sequence
Recognition and Its Application to Scene Text Recognition by B Shi et al. https://arxiv.org/pdf/1507.05717.pdf
##
Dataset used: IAM Dataset. It can be found here: https://fki.tic.heia-fr.ch/databases/iam-handwriting-database

Dataset used is a lot smaller than that used in the paper. Therefore have not created as deep a model as the one mentioned in the paper.
##
If you find this repository useful, please cite the following:-
~~~
 @misc{Shreshta2021OCR,
   author = {Shetty, Shreshta}, 
   title = {OCR}, 
   year = {2021}, 
   publisher = {GitHub}, 
   journal = {GitHub repository}, 
   howpublished = {\url{https://github.com/shreshtashetty/OCR}},
 }
 ~~~
