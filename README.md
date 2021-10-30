# Plant Segementation

This project is to apply **semantic segementation** on **plant images**. Original plant images are downloaded from google image search and cropped to a squared fix size. Mask images are generated using [PlantCV](https://plantcv.readthedocs.io/en/stable/) package and manual manipulation in MS Paint. The backgroud is painted by black color while the plant area is highlighted by white color. `plantcv` is not needed to run trainer and predictor.

[Deeplabv3](https://pytorch.org/hub/pytorch_vision_deeplabv3_resnet101/) pre-trained deeplabv3_resnet50 model developed by Pytorch Team is tuned to fit this plant image dataset. Only 50 paired plant images as inputs can already enable the model to have good performance.

Mandatory python packages:
- torch (cpu/cuda)
- torchvision
- PIL
- matplotlib

<p align="center">
  <img src=".\images\data.png" width=600 />
</p>

## Training Loss And Performance Tracking

<p align="center">
  <img src=".\images\training.png" width=600 />
</p>

## Testing Trained Model With New Images

<p align="center">
  <img src=".\images\out.jpg" width=600 />
</p>


