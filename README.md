# Exploring Diverse Representations for Open Set Recognition

Official PyTorch Implementation of Our Work *[AAAI2024] Exploring Diverse Representations for Open Set Recognition*. 

[[arXiv](https://arxiv.org/pdf/2401.06521.pdf)]


## TestRun2
### TestRun2 Environment

- Python 3.14.0
- Pytorch 2.10.0
- CUDA 13.0

### Requirements
- easydict
- numpy
- Pillow
- PyYAML
- scikit_learn

### Description

Testing different ~score_wgts~ from the ~osr.yml~ file.

### Train

Training from scratch:
```
python osr_main.py -g {GPU_ID} -d cifar10
```

## File organization 📑

The `core` folder contains model, training, and testing code, the `datasets` folder contains data loading and preprocessing code, and the `misc` folder contains other auxiliary code. The output and result will be saved in `logs` folder.
