# AlexNet

### The original article
- [ImageNet Classification with Deep Convolutional Neural Networks](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks)

We adjust the conv kernel of first layer to **5x5** and stride **2** because our image size is only 64x64 compared to original 224x224. This model finally achieves about **97.4%** accuracy in val with 116s/epoch.
![](./alexnet.jpeg)
