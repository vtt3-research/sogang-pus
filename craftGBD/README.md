# Object Detection

Object detection using CraftGBD

## Requirements

* Python2.7
* Caffe

## Installation : CraftGBD
```
git clone --recursive https://github.com/craftGBD/craftGBD.git
```

## Testing

All of the following steps are based on the assumption that the previous installation has been completed.

#### Download dataset

* run fetch_data/fetch_eval_data.m to download test images and scripts.

#### Testing

After fully installing craftGBD, testing the model can be done by running ./run_test_multiGPU_ResNet_GBD_accurate.sh in the evaluation folder.

```
sudo ./run_test_multiGPU_ResNet_GBD_accurate.sh
```
## Training

To be updated

## Result

See the result.txt file.

## References

https://github.com/craftGBD/craftGBD

[1] Zeng, Xingyu, et al. "Crafting gbd-net for object detection." IEEE transactions on pattern analysis and machine intelligence (2017).