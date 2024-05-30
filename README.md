# Wakeup-Darkness: When Multimodal Meets Unsupervised Low-light Image Enhancement
# SAM's segment results in low-light images
我们探索了SAM在低光照下的分割结果，如下图所示
![image](https://github.com/zhangbaijin/enlighten-anything/blob/main/semantic.png)

## Model
`weights/`
`model.py` 
`fuse_block.py`

## Dataset processing
you should run the `sam.py` to produce the segment image like LOL/LIME/SCIE

## Train and Test

`python train.py --arc WithoutCalNet --batch_size 10`

`python test.py`

## Citations
```
 @article{Zhao_Zhang_Tang_Gu_Zhu_2023,  
 title={Enlighten-anything:When Segment Anything Model Meets Low-light Image Enhancement}, 
 author={Zhang, Xiaofeng, Qihan Zhao and Tang, Hao and Gu, Chaochen and Zhu, Shanying}, 
 year={2023}, 
 month={Jun}, 
 language={en-US} 
 }
```
