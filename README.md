# GenderGoogleNet

Inference code for GenderGoogleNet model which available on [onnx/models](https://github.com/onnx/models/tree/main/validated/vision/body_analysis/age_gender) repository. 

# Installation

```shell
pip install -r requirements.txt
```

# Pretrained models

| Name            | Link                                                                                              |
|-----------------|---------------------------------------------------------------------------------------------------|
| GenderGoogleNet | [ONNX](https://github.com/clibdev/gendergooglenet/releases/latest/download/gender-googlenet.onnx) |

# Inference

```shell
python test.py --model-path gender-googlenet.onnx --image-path data/test.jpg
```
