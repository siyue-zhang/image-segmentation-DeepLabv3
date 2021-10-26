# Project Introduction

This project is to apply **semantic segementation** on **plant images**. Original plant images are downloaded from google image search and cropped to a squared fix size. Mask images are generated using [PlantCV](https://plantcv.readthedocs.io/en/stable/) package and manual manipulation. The backgroud is painted by black color while the plant area is highlighted by white color.

[Deeplabv3](https://pytorch.org/hub/pytorch_vision_deeplabv3_resnet101/) pre-trained model developed by Pytorch Team is tuned to fit this plant image dataset.

<img src=".\images\data.png" width=600/>
