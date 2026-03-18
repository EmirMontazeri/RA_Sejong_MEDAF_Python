# Exploring Diverse Representations for Open Set Recognition

Official PyTorch Implementation of Our Work *[AAAI2024] Exploring Diverse Representations for Open Set Recognition*. 

[[arXiv](https://arxiv.org/pdf/2401.06521.pdf)]


## TestRun1
### TestRun1 Environment

- Python 3.14.0
- Pytorch 2.10.0
- CUDA 13.0

### Requirements
- easydict
- numpy
- Pillow
- PyYAML
- scikit_learn

### Dataset

Before starting the model training, you need to modify the paths of the datasets in `osr_loader.py`. 

Apart from common datasets (CIFAR10, SVHN, CIFAR100), the rest of the datasets need to be manually downloaded and placed in the correct path.

The pre-defined split information is in `misc/util.py`.

### Train

Training from scratch:
```
python osr_main.py -g {GPU_ID} -d cifar10
```

## File organization 📑

The `core` folder contains model, training, and testing code, the `datasets` folder contains data loading and preprocessing code, and the `misc` folder contains other auxiliary code. The output and result will be saved in `logs` folder.
