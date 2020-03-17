# WGAN-pytorch
A pytorch implementation of [Wasserstein GAN](https://arxiv.org/abs/1701.07875) which improve the stability of learning by using approximated wasserstein distance.


## Result

LSUN - conference room - 15eps


 |WGAN-weight clipping with Batch normalization | WGAN-weight clipping without Batch normalization|                                   
 |:---: | :---:|                                       
 |<img src="./assets/wgan-wc-bn-LSUN_conference_room.gif">|<img src="./assets/wgan-wc-LSUN_conference_room.gif">|



 |WGAN-weight clipping with Batch normalization | WGAN-weight clipping without Batch normalization|                                   
 |:---: | :---:|                                       
 |<img src="./assets/WGAN-wc-bn-LSUN_conference_room.png">|<img src="./assets/wgan-wc-LSUN_conference_room.png">|
