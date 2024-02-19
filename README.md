# Enlighten Anything: When Segment Anything Model Meets Low-Light Image Enhancement 
# SAM's segment results in low-light images
我们探索了SAM在低光照下的分割结果，如下图所示
![image](https://github.com/zhangbaijin/enlighten-anything/blob/main/semantic.png)

## Dataset processing
you should run the `sam.py` to produce the segment image like LOL/LIME/SCIE
## Train and Test

`python train.py --arc WithoutCalNet --batch_size 10`

`python test.py`
