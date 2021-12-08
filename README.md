# Veriff
STN and proposed work.

![stn](https://user-images.githubusercontent.com/15413922/145271324-d23d20e4-ce30-4901-b8bd-856d282224ed.png)

The idea of spatial transformer networks or STNs was introduced by DeepMind, it makes use of image transformations specifically, Affine Transformation to transform the image feature map. We can also say that spatial transformer networks are a generalization of differentiable attention to any spatial transformation. Spatial transformer networks (STNs) teach a neural network how to make spatial transformations on an input image to improve the model's geometric invariance. It can, for example, crop a specific area of interest, scale, and rotate an image. Because CNNs are not invariant to rotation, scaling, and other affine transformations, it can be a valuable method. Further details can be explored in the paper Spatial Transformer Networks (https://arxiv.org/abs/1506.02025)

The code is written in PyTorch. There is no GPU required, everything can be run on CPU.

Setting up the run enviroment:

Install conda on your system: https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html

Now the next step is to create a virtual enviroment for the implementation using conda:
Please follow the instruction in: https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html

The next step is to activate the enviroment and installing the requirements.txt
