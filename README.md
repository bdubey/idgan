# ID-GAN 
This repo is to reproduce the result of paper [High-Fidelity Synthesis with Disentangled Representation](https://arxiv.org/abs/2001.04296)

## DATA
From [celbA website](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)  download `img_align_celeba.zip` file to data directory.

## Train VAE
`python vae_train.py`

## Train GAN
`python gan_train.py`

## Generate Images by the trained generator
Use the code in `idgan_demo.ipynb` to generate new samples.
 ![Samples](https://github.com/bdubey/idgan-high_fi_synthesis_with_disentangled_representation/blob/master/imgs/generated.png)
## References
* Link to the paper [High-Fidelity Synthesis with Disentangled Representation](https://arxiv.org/abs/2001.04296)
