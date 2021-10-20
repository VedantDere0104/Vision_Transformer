# AN IMAGE IS WORTH 16X16 WORDS: TRANSFORMERS FOR IMAGE RECOGNITION AT SCALE

Pytorch implementation of Vision Transformer. It is used as a backbone network for Object Detection , Instance Segmentation .

## Abstract :- 
While the Transformer architecture has become the de-facto standard for natural
language processing tasks, its applications to computer vision remain limited. In
vision, attention is either applied in conjunction with convolutional networks, or
used to replace certain components of convolutional networks while keeping their
overall structure in place. We show that this reliance on CNNs is not necessary
and a pure transformer applied directly to sequences of image patches can perform
very well on image classification tasks. When pre-trained on large amounts of
data and transferred to multiple mid-sized or small image recognition benchmarks
(ImageNet, CIFAR-100, VTAB, etc.), Vision Transformer (ViT) attains excellent
results compared to state-of-the-art convolutional networks while requiring substantially fewer computational resources to train.

## Architecture :- 
![image](https://user-images.githubusercontent.com/76057253/138115716-693d8911-47e0-45bb-a861-0f549c3b7f79.png)

ViT uses the same Transformer architecture from NLP Transformer .

### Transformer Encoder :- 
![image](https://user-images.githubusercontent.com/76057253/138115894-da79557d-9889-467b-921c-a3d079abb75a.png)


## Results :- 
![image](https://user-images.githubusercontent.com/76057253/138116044-524e946b-a09f-4ab7-be1c-563924db53a0.png)
