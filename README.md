# I’m Something of a Painter Myself CycleGAN-Monet
This project covers the Kaggle intoduction to GAN models, especially CycleGAN. The CycleGAN is an extension of the GAN architecture that involves the simultaneous training of two generator models and two discriminator models, its mainly used for style transfer in this project.

One generator takes images from the first domain as input and outputs images for the second domain, and the other generator takes images from the second domain as input and generates images for the first domain. Discriminator models are then used to determine how plausible the generated images are and update the generator models accordingly. In essence CycleGANs are extended architecture over the simple GAN.

In the course we were taught general GANs only, old assignment also covered simple GANs where we create One Generator and one Discriminator based Deep Convolutional Generative Adversarial Network. However since this assignment covers the topics not covered in the course we have accessed various blogposts, videos, and Kaggle introductry notebooks to create this project.

Dataset is based on the Kaggle I’m Something of a Painter Myself competition: https://www.kaggle.com/competitions/gan-getting-started

We are tasked to create a CycleGAN which is able to apply transfer learning and transfer the monet style to non monet styled images.

We are given 300 Monet Images and 7038 Other images. In the submission we will submit the monet converted images to the Kaggle competition.
