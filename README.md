# Art_Generation_With_Neural_Style_Transfer
Implementation of Neural Style Transfer
Neural Style Transfer (NST) is one of the most fun and interesting optimization techniques in deep learning. It merges two images, namely: a "content" image (C) and a "style" image (S), to create a "generated" image (G). The generated image G combines the "content" of the image C with the "style" of image S.

### Transfer Learning
Neural Style Transfer (NST) uses a previously trained convolutional network, and builds on top of that. The idea of using a network trained on a different task and applying it to a new task is called transfer learning.

I have used the the epynomously named VGG network from the original NST paper published by the Visual Geometry Group at University of Oxford in 2014. Specifically, VGG-19, a 19-layer version of the VGG network. This model has already been trained on the very large ImageNet database, and has learned to recognize a variety of low level features (at the shallower layers) and high level features (at the deeper layers).

The further information regarding the paper and the implemetation logic have been attatched inside the ipynb file in the repo.
