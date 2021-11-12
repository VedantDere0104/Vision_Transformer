# Swin Transformer: Hierarchical Vision Transformer using Shifted Windows :-

Pytorch implementation of Swin Transformer . It is used as a backbone architecture in object detection or segmentation.

## Abstract :- 
This paper presents a new vision Transformer, called
Swin Transformer, that capably serves as a general-purpose
backbone for computer vision. Challenges in adapting
Transformer from language to vision arise from differences
between the two domains, such as large variations in the
scale of visual entities and the high resolution of pixels
in images compared to words in text. To address these
differences, we propose a hierarchical Transformer whose
representation is computed with Shifted windows. The
shifted windowing scheme brings greater efficiency by limiting self-attention computation to non-overlapping local
windows while also allowing for cross-window connection.
This hierarchical architecture has the flexibility to model
at various scales and has linear computational complexity
with respect to image size. These qualities of Swin Transformer make it compatible with a broad range of vision
tasks, including image classification (87.3 top-1 accuracy
on ImageNet-1K) and dense prediction tasks such as object
detection (58.7 box AP and 51.1 mask AP on COCO testdev) and semantic segmentation (53.5 mIoU on ADE20K
val). Its performance surpasses the previous state-of-theart by a large margin of +2.7 box AP and +2.6 mask AP on
COCO, and +3.2 mIoU on ADE20K, demonstrating the potential of Transformer-based models as vision backbones.
The hierarchical design and the shifted window approach
also prove beneficial for all-MLP architectures.

## Architecture :- 
![image](https://user-images.githubusercontent.com/76057253/141417890-205ef441-18bb-4646-8066-0ce59c5362a8.png)

Shifted Window Approach :- 
![image](https://user-images.githubusercontent.com/76057253/141417986-0526a2f7-837d-4c1e-8d34-760aac7e4689.png)

Swin Transformer vs ViT :- 
![image](https://user-images.githubusercontent.com/76057253/141418174-a365048d-19b5-4e08-914e-168d8a4ed190.png)

Architecture Specification :- 
![2021-11-12](https://user-images.githubusercontent.com/76057253/141418450-332d15a6-f3ca-4d13-8862-5764e953a58e.png)

## Results :- 
![image](https://user-images.githubusercontent.com/76057253/141418523-f1b4f5a8-430e-45e0-b5db-fd16f7df66e7.png)

```
@misc{liu2021swin,
      title={Swin Transformer: Hierarchical Vision Transformer using Shifted Windows}, 
      author={Ze Liu and Yutong Lin and Yue Cao and Han Hu and Yixuan Wei and Zheng Zhang and Stephen Lin and Baining Guo},
      year={2021},
      eprint={2103.14030},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
