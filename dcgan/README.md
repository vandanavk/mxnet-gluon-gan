# DCGAN using Apache MXNet

It is recommended to execute this example on GPU.

2 options to try out this notebook:
1. [Run this notebook on Colab](https://colab.research.google.com/github/piyushghai/mxnet-gluon-gan/blob/dcgan/dcgan/dcgan_faces.ipynb)
    
    Pre-requisites to execute on Colab: Select Python, GPU as the runtime, CUDA 9.2 and MXNet 1.4.0 (mxnet-cu92) installed.
    
    Note: The step to install these pre-requisites is already included in the notebook.
2. [Try this notebook in Amazon Sagemaker](https://docs.aws.amazon.com/sagemaker/latest/dg/nbi.html)
    
    Pre-requisites to execute on SageMaker: Clone this GitHub repo in SageMaker (switch to dcgan branch), select MXNet_p36 as the kernel.
    
    Note: Enabling this kernel, makes the correct version of MXNet & CUDA automatically available for use in SageMaker. 


## References

Datasets:
* Classrooms: https://www.yf.io/p/lsun
* Flowers: http://www.robots.ox.ac.uk/~vgg/data/flowers/102/index.html
* Cartoons: https://google.github.io/cartoonset/download.html
* Faces: http://vis-www.cs.umass.edu/lfw/

Papers/websites:
* DCGAN paper: https://arxiv.org/pdf/1511.06434.pdf
* Gluon- The Straight Dope: https://github.com/zackchase/mxnet-the-straight-dope/blob/master/chapter14_generative-adversarial-networks/dcgan.ipynb 
* Introduction to Generative Adversarial Networks (GAN) with Apache MXNet - AWS Online Tech Talks: https://www.youtube.com/watch?reload=9&v=4fQRoBz0BnM
* Machine Learning is Fun Part 7: Abusing Generative Adversarial Networks to Make 8-bit Pixel Art: https://medium.com/@ageitgey/abusing-generative-adversarial-networks-to-make-8-bit-pixel-art-e45d9b96cee7
* Keep Calm and train a GAN. Pitfalls and Tips on training Generative Adversarial Networks: https://medium.com/@utk.is.here/keep-calm-and-train-a-gan-pitfalls-and-tips-on-training-generative-adversarial-networks-edd529764aa9

