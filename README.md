# GenderGoogleNet

Inference code for GenderGoogleNet model which available on [onnx/models](https://github.com/onnx/models/tree/main/validated/vision/body_analysis/age_gender) repository. 

# Installation

```shell
pip install -r requirements.txt
```

# Pretrained models

| Name            | Model Size (MB) | Link                                                                                              | SHA-256                                                          |
|-----------------|-----------------|---------------------------------------------------------------------------------------------------|------------------------------------------------------------------|
| GenderGoogleNet | 22.8            | [ONNX](https://github.com/clibdev/gendergooglenet/releases/latest/download/gender-googlenet.onnx) | af24a4eaa9eaf70913cc9a337a0387c86f11549cbd9bbc16bffeefcdcf88cbf4 |

# Inference

```shell
python test.py --model-path gender-googlenet.onnx --image-path data/test.jpg
```
