# Digital-Forensics

DF project to train a Generative Adversarial Network.
In this project, I built and trainned an adversarial network that took in a fashion MINT dataset.
The netwotk consists of two parts, the generator and discriminator. The genrator produced images that resembled the fashion data and these where fed into the discriminator to categorise them as fake or real.
When the images are rejected by the discriminator, the generator learns that it needs to improve in making better images that resemble the real images.

So the generator trained on becoming better to fool the discriminator and the discriminator trained on becoming better in categorising fake and real fashion data.

[Dataset used](https://www.kaggle.com/datasets/zalando-research/fashionmnist)
