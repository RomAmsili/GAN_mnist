 # GAN MNIST

This repository contains a implementation of a Generative Adversarial Network (GAN) and Conditional GAN (C-GAN) for generating new images of handwritten digits similar to the MNIST dataset. The C-GAN is trained with the class labels of the digits, so that it can generate images of a specific digit.

## Requirements

To run this notebook, you will need the following libraries:
- Pytorch
- Matplotlib

You can install these libraries by running `pip install torch torchvision matplotlib` in your command prompt.

## Data

The MNIST dataset is used for training the GAN and C-GAN. This dataset contains 60,000 28x28 grayscale images of handwritten digits, along with their corresponding labels.

## Model

The GAN and C-GAN consist of two main components: the generator and the discriminator. The generator is responsible for creating new images, while the discriminator is responsible for determining whether an image is real or generated. The generator and discriminator are trained simultaneously, with the goal of the generator producing images that can fool the discriminator into thinking they are real.

The C-GAN also receives class labels as input, so that it can generate images of a specific digit.

## Training

The GAN and C-GAN are trained for 250 epochs. After each epoch, the generator and discriminator are both updated based on their performance. The generated images are also plotted to show the progress of the training.

![image](https://user-images.githubusercontent.com/82934994/214012458-3c072d16-c87d-4304-9691-8b03f0573ab3.png)

## Results

The GAN and C-GAN are able to generate new images of handwritten digits that are similar to the MNIST dataset. As the training progresses, the generated images become increasingly realistic. With the C-GAN, it is possible to generate images of a specific digit by providing the corresponding class label.

![image](https://user-images.githubusercontent.com/82934994/214012311-64dddf7e-01a0-4573-9d33-7c6b514b5be7.png)

![image](https://user-images.githubusercontent.com/82934994/214012386-2a943e26-7a0c-435c-ac99-7f33d4f89482.png)


## Instructions

1. Clone the repository
2. Install the required libraries
3. Run the GAN.ipynb on Jupyter notebook
4. Follow the instruction in the notebook
5. enjoy the results

## Conclusion

This GAN and C-GAN are basic models, but they demonstrate the potential of GANs for generating new, realistic images. With further training and optimization, GANs could be used for a variety of applications such as image generation, style transfer, and more.
