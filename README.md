## ResNet Model on Tiny ImageNet

Deep Residual networks (ResNets), makes training process easier and faster.
It also achieves better accuracy compared to their equivalent neural networks.
Deep Residual Networks have been proven to be a very successful model on image classification.
In this project, we have trained our own ResNets for the Tiny ImageNet Visual Recognition - an
image classification task based on a subset of the ImageNet. The main difference in ResNets is
that they have shortcut connections parallel to their normal convolutional layers. These shortcut
are always alive and gradients can easily propagate through them, resulting in faster training.

Trained ResNet 50 on Tiny ImageNet data. The Image classification models was trained from scratch.
Preventing overfitting is an essential problem to overcome, especially for Tiny ImageNet, we used
data augmentation to prevent over-fitting.
