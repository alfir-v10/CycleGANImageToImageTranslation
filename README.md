# CycleGAN: Imag-to-Image Translation
Summer to Winter Translation

## Purpose of project: 
   Implement the change of seasons in the photo, the change of winter and summer landscapes.

## Goals pursued:
  * Learning PyTorch
  * Review articles and papers on the topic Image-to-Image Translation
  * Implement CycleGAN architectures
  * Train CycleGAN

## What is CycleGAN?
The [CycleGAN](https://machinelearningmastery.com/what-is-cyclegan/#:~:text=The%20CycleGAN%20is%20a%20technique,be%20related%20in%20any%20way.) is a technique that involves the automatic training of image-to-image translation models without paired examples. The models are trained in an unsupervised manner using a collection of images from the source and target domain that do not need to be related in any way. Read more: [Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks](https://junyanz.github.io/CycleGAN/) [CycleGAN GitHub Page](https://github.com/junyanz/CycleGAN)

<div align='center'>
  
  CycleGAN Architecture
  ![](https://raw.githubusercontent.com/yunjey/mnist-svhn-transfer/master/gif/cyclegan.png)
</div>

<div align='center'>
  
  Generator Architecture
  ![](https://raw.githubusercontent.com/vjrahil/CycleGAN-in-Pytorch/cbe44b5097cfd876f299e31abfe98d8d578760cb/notebook_images/cyclegan_generator_ex.png)
</div>
  
<div align='center'>
  
  Discriminator Architecture
![](https://raw.githubusercontent.com/vjrahil/CycleGAN-in-Pytorch/cbe44b5097cfd876f299e31abfe98d8d578760cb/notebook_images/discriminator_layers.png)
</div>

<div align='center'>
  
  Implementation of cycle-consistency loss
![](https://github.com/vjrahil/CycleGAN-in-Pytorch/raw/cbe44b5097cfd876f299e31abfe98d8d578760cb/notebook_images/CycleGAN_loss.png)
</div>

## Which dataset is used?
[Summer2Winter Yosemite](https://www.kaggle.com/balraj98/summer2winter-yosemite/version/1) dataset consists of 1540 Summer Photos & 1200 Winter Photos with each split into train and test subsets.

![](https://github.com/alfir-v10/CycleGANImageToImageTranslation/blob/main/best%20results/summer.png?raw=true)
![](https://github.com/alfir-v10/CycleGANImageToImageTranslation/blob/main/best%20results/winter.png?raw=true)

## The results obtained

<div align='center'>

  <b>Summer2Winter Yosemite dataset</b>
  
  Summer to Winter
![](https://github.com/alfir-v10/CycleGANImageToImageTranslation/blob/main/best%20results/sample-004700-X-Y.png?raw=true)
  Winter to Summer
![](https://github.com/alfir-v10/CycleGANImageToImageTranslation/blob/main/best%20results/sample-004700-Y-X.png?raw=true)
  
  <b>A set of random images of Kazan</b>
  
  Summer to Winter
![](https://github.com/alfir-v10/CycleGANImageToImageTranslation/blob/main/best%20results/kazan-sample-004700-X-Y.png?raw=true)
  Winter to Summer
![](https://github.com/alfir-v10/CycleGANImageToImageTranslation/blob/main/best%20results/kazan-sample-004700-Y-X.png?raw=true)

</div>

## Articles used:
* [Overview of CycleGAN architecture and training](https://towardsdatascience.com/overview-of-cyclegan-architecture-and-training-afee31612a2f)
* [Image-to-Image Translation using CycleGAN Model](https://towardsdatascience.com/image-to-image-translation-using-cyclegan-model-d58cfff04755)
* [CycleGAN Summer->Winter Image Translation PyTorch](https://www.kaggle.com/balraj98/cyclegan-summer-winter-image-translation-pytorch)
* [Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks](https://arxiv.org/pdf/1703.10593.pdf)
* [CS231n Convolutional Neural Networks for Visual Recognition](https://cs231n.github.io/convolutional-networks/#conv)
* [Deep Residual Learning for Image Recognition](https://arxiv.org/pdf/1512.03385.pdf)
* [Residual blocks — Building blocks of ResNet](https://towardsdatascience.com/residual-blocks-building-blocks-of-resnet-fd90ca15d6ec)
* [Least Squares Generative Adversarial Networks](https://arxiv.org/pdf/1611.04076.pdf)
* [Guide to Pytorch Learning Rate Scheduling](https://www.kaggle.com/isbhargav/guide-to-pytorch-learning-rate-scheduling)
* [CycleGAN with Better Cycles](https://ssnl.github.io/better_cycles/report.pdf)
