## Bilevel Optimization with Lower-Level Uniform Convexity: Theory and Algorithm

This is the code for ICLR 2026 paper of "[Bilevel Optimization with Lower-Level Uniform Convexity: Theory and Algorithm](https://openreview.net/pdf?id=dJgb3ngAvT)".

To run data hyper-cleaning on SNLI experiments, you should 
- Download SNLI data first, or directly download the preprocessed version from [link](https://drive.google.com/drive/folders/1O4mYzCpd84Nu2wXGoocTmGYzfqg9D5P-).

- Create 'data' directory in the current path by `mkdir data` and put all the data files in `data/` directory.


### Requirements
- Pytorch 2.0  
- numpy
- sklearn
- tqdm


### Run our algorithm "unibio" on data hyper-cleaning by
```bash
    python main.py --methods unibio 
```

### Run bilevel synthetic experiments by

```bash
    python synthetic_exp.py
```

### Citation
If you find our repository helpful, please cite our paper:
```
@inproceedings{
wu2026bilevel,
title={Bilevel Optimization with Lower-Level Uniform Convexity: Theory and Algorithm},
author={Wu, Yuman and Gong, Xiaochuan and Hao, Jie and Liu, Mingrui},
booktitle={The Fourteenth International Conference on Learning Representations},
year={2026},
url={https://openreview.net/forum?id=dJgb3ngAvT}
}
```
