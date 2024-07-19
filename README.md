# GUME: Graphs and User Modalities Enhancement for Long-Tail Multimodal Recommendation

<!-- PROJECT LOGO -->

## Introduction

This is the Pytorch implementation for our GUME paper:

>GUME: Graphs and User Modalities Enhancement for Long-Tail Multimodal Recommendation

## Environment Requirement
- python 3.7.11
- Pytorch 1.11.0

## Dataset

We provide three processed datasets: Baby, Sports, Clothing, Electronics.

Download from Google Drive: [Baby/Sports/Clothing/Electronics](https://drive.google.com/drive/folders/1tU4IxYbLXMkp_DbIOPGvCry16uPvolLk)

## Training
  ```
  cd ./src
  python main.py
  ```
## Performance Comparison
<img src="image/result.png" width="900px" height="380px"/>

## Citing GUME
If you find GUME useful in your research, please consider citing our [paper](https://arxiv.org/).
```
# @article{xu2024mentor,
#   title={MENTOR: Multi-level Self-supervised Learning for Multimodal Recommendation},
#   author={Jinfeng Xu and Zheyu Chen and Shuo Yang and Jinze Li and Hewei Wang and Edith C. -H. Ngai},
#   journal={arXiv preprint arXiv:2402.19407},
#   year={2024}
# }
```
The code is released for academic research use only. For commercial use, please contact [Guojiao Lin](guojiaolin37@gmail.com).


## Acknowledgement
The structure of this code is  based on [MMRec](https://github.com/enoche/MMRec). Thank for their work.
