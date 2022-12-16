# Evaluating the Effectiveness of Masked Autoencoders for Computer Vision
This is done as part of Deep Learning, Advanced Course DD2412 at KTH.

## About
The aim of the project is replicate the results of the paper "Masked Autoencoders Are Scalable Vision Learners". 

## Experimental setup:
Our approach involved constructing an asymmetric encoder-decoder architecture with a ViT-B/16 encoder and a simple decoder. After self-supervised pre-training,
we focused on supervised training for evaluating the representations with linear probing.

## Resources
To replicate within limited compuattion resources, we restricted our experiments to Imagenette dataset. 

## References
Masked Autoencoders Are Scalable Vision Learners: https://arxiv.org/pdf/2111.06377.pdf
