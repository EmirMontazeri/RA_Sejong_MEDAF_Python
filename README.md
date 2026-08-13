# Experimenting on "Exploring Diverse Representations for Open Set Recognition"

Original Paper *[AAAI2024] Exploring Diverse Representations for Open Set Recognition*. 
[[arXiv](https://arxiv.org/pdf/2401.06521.pdf)]

## Experimental Run
### Environment

- Python 3.14.0
- Pytorch 2.10.0
- CUDA 13.0

### Requirements
- easydict
- numpy
- Pillow
- PyYAML
- scikit_learn

### Train

```
python osr_main.py -g {GPU_ID} -d {DATASET}
```