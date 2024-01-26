# Monet Style GAN
This GAN (Generative Adversarial Network) was designed to satisfy a weekly homework at the University of Colorado in the Deep Learning Class. This code takes input images of Monet Paintings and Photos and learns how to make a "Monet Style" image from photos. The cyclical training of the neural network is comprised of a generator and a discriminator tied together with skip functions. The final output is then scored in this ongoing competition on Kaggle: https://www.kaggle.com/competitions/gan-getting-started/overview

The Dataset used for this notebook is comprised of 300 Monet Painting images, and 7038 Photos. Each jpg is resized to 256 by 256 pixels and in RGB color format. The dataset is available here: https://www.kaggle.com/competitions/gan-getting-started/data

The final notebook for class is located here:
https://github.com/tbonesteaks/monetgan/monet-generator.ipynb
