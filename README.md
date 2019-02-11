# style_transfer

The following repository contains a basic implementation of style transfer algorithm using a single style and content image. Style transfer basically produces artwork by tranferring style of one image to the content of the other image using the concept of gram matrix. We have used the vgg19 pretrained network on image classification in order to access the intermediate layers for style and content transfer. This is possible because the model serves as a complex feature extractor; hence by accessing intermediate layers we’re able to describe the content and style of input images.
The code has implemented in google colab due to the constraint of computational resource. Main libraries used are -

1. numpy
2. keras
3. functools
4. matplotlib
5. PIL 
6. time
7. tensorflow (as backend)

