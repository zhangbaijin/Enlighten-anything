# Enlighten Anything: When Segment Anything Model Meets Low-Light Image Enhancement 
Qihan Zhao, Xiaofeng Zhang, Hao Tang, Chaochen Gu, Shanying Zhu

[[Code](https://github.com/QihanZhao/enlighten-anything)]
[[Paper](https://arxiv.org/abs/2306.10286)]

# SAM's segment results in low-light images
我们探索了SAM在低光照下的分割结果，如下图所示
![image](https://github.com/zhangbaijin/enlighten-anything/blob/main/semantic.png)
# SAM's compare results with sota mehtod
在SICE上的对比结果如下图
![image](https://github.com/zhangbaijin/enlighten-anything/blob/main/compare-lime.png)
## Data
`data/`
`dataset.py`

## Model
`weights/`
`model.py` 
`fuse_block.py`

## Criterion
`loss.py`

## Utils
`segment_anything/`
`sam.py`
`utils.py`

## Train and Test
`train.py`
`test.py`
`evaluate.py`
