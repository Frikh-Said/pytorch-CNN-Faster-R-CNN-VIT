# pytorch-CNN-Faster-R-CNN-VIT


This lab aims to explore PyTorch's capabilities in computer vision by constructing CNN and Faster R-CNN architectures for MNIST classification. Additionally,the lab delves into Vision Transformers (ViT) by implementing one from scratch and evaluating its performance on MNIST, followed by a comparison with traditional CNN and Faster R-CNN approaches.

## Convolutional Neural Network (CNN):
CNNs are deep neural networks tailored for processing grid-structured data like images. They employ convolutional layers to extract features and pooling layers to reduce spatial dimensions, enabling tasks such as image classification and object detection.

## Faster R-CNN:
Faster R-CNN is an object detection framework consisting of a region proposal network (RPN) and a region-based CNN. RPN generates object proposals, refined by R-CNN, enabling efficient object detection by combining region proposal and classification.

## Vision Transformer (ViT):
ViT is a transformer-based architecture for computer vision tasks, breaking down images into fixed-size patches processed by transformer blocks. By utilizing self-attention, ViT captures global context information, enabling effective image classification without convolutional layers.

## Difference between CNN, Faster R-CNN, and ViT:

### Architecture
 CNNs rely on convolutional layers to extract hierarchical features from input images, whereas Faster R-CNN incorporates both region proposal and region-based CNNs for object detection. On the other hand, ViT adopts a transformer architecture that processes image patches directly without convolutional layers.

### Complexity and Performance
 CNNs are computationally efficient and widely used in various computer vision tasks, including image classification and segmentation. Faster R-CNN offers state-of-the-art performance in object detection but requires more complex architecture and training procedures. ViT, while promising, is still relatively new and may require extensive tuning for optimal performance compared to traditional CNN-based approaches.

## DATASET

### - MINST DATASET : [MINST DATASET](https://www.kaggle.com/datasets/hojjatk/mnist-dataset)

