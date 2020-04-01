# WGAN-pytorch
Pytorch implementations of [Wasserstein GAN](https://arxiv.org/abs/1701.07875) which improve the stability of learning by using approximated wasserstein distance and [Improved Training of Wasserstein GANs](https://arxiv.org/abs/1704.00028) which propose an alternative to clipping weights: penalize the norm of gradient of the critic with respect to its input.

<img src="./assets/wgan-figure.PNG" width="80%">

<img src="./assets/wgan-gp-figure.PNG" width="80%">


## Result

LSUN - conference room

### Weight Cliipping

 |WGAN-weight clipping | WGAN-weight clipping with BatchNorm|                                   
 |:---: | :---:|                                       
 |<img src="./assets/wgan-wc-LSUN_conference_room.gif" width="45%">|<img src="./assets/wgan-wc-bn-LSUN_conference_room.gif" width="45%">|


 |WGAN-weight clipping | WGAN-weight clipping with BatchNorm|                                   
 |:---: | :---:|                                       
 |<img src="./assets/wgan-wc-LSUN_conference_room.png" width="45%" >|<img src="./assets/WGAN-wc-bn-LSUN_conference_room.png" width="45%">|

### Gradient Penalty

 |WGAN-gradient penalty | WGAN-gradient penalty with LayerNorm|                                   
 |:---: | :---:|                                       
 |<img src="./assets/wgan-gp-LSUN_conference_room.gif" width="45%">| <img src="./assets/wgan-gp-ln-LSUN_conference_room.gif" width="45%"> |
 
 
  |WGAN-gradient penalty | WGAN-gradient penalty with LayerNorm|                                   
 |:---: | :---:|                                       
 |<img src="./assets/wgan-gp-LSUN_conference_room.png" width="45%">| <img src="./assets/wgan-gp-ln-LSUN_conference_room.gif" width="45%"> |