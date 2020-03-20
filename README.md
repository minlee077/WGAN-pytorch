# WGAN-pytorch
pytorch implementations of [Wasserstein GAN](https://arxiv.org/abs/1701.07875) which improve the stability of learning by using approximated wasserstein distance and [Improved Training of Wasserstein GANs](https://arxiv.org/abs/1704.00028) which propose an alternative to clipping weights: penalize the norm of gradient of the critic with respect to its input..


## Result

LSUN - conference room

### Weight Cliipping

 |WGAN-weight clipping | WGAN-weight clipping with BatchNorm|                                   
 |:---: | :---:|                                       
 |<img src="./assets/wgan-wc-LSUN_conference_room.gif">|<img src="./assets/wgan-wc-bn-LSUN_conference_room.gif">|


 |WGAN-weight clipping | WGAN-weight clipping with BatchNorm|                                   
 |:---: | :---:|                                       
 |<img src="./assets/wgan-wc-LSUN_conference_room.png">|<img src="./assets/WGAN-wc-bn-LSUN_conference_room.png">|

### Gradient Penalty

 |WGAN-gradient penalty | WGAN-gradient penalty with LayerNorm|                                   
 |:---: | :---:|                                       
 |<img src="./assets/wgan-gp-LSUN_conference_room.gif">|TBD|
 
 
  |WGAN-gradient penalty | WGAN-gradient penalty with LayerNorm|                                   
 |:---: | :---:|                                       
 |<img src="./assets/wgan-gp-LSUN_conference_room.png">|TBD|