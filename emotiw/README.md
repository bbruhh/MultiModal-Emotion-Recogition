# EmotiW

Code for Emotion Recognition in the Wild (EmotiW) challenge

For EmotiW 2017 code please see folder [2017](https://github.com/bknyaz/emotiw/tree/master/2017)

## Description

cd to folder 2017, then run the code as: ```python3 submission5.py```

The code will download all necessary features precomputed using our models, train emotion classification models and predict emotions on the test set.

Test accuracy is 60.03% (second place).

### Requirements
- Python3 (necessary to load features saved in python3)

### Test environment
- Ubuntu 14.04 LTS

## References

[Challenge website](https://sites.google.com/site/emotiwchallenge/home)

Paper:
[`Convolutional neural networks pretrained on large face recognition datasets for emotion classification from video`](https://arxiv.org/abs/1711.04598) accepted to the 1st	Workshop on Large-scale	Emotion	
Recognition	and	Analysis. IEEE	International	Conference	on	Automatic	Face	and	Gesture	
Recognition	2018, Xi'an, China

If you use our code or features in your work, please cite our paper as following:
```
@article{knyazev2017convolutional,
  title={Convolutional neural networks pretrained on large face recognition datasets for emotion classification from video},
  author={Knyazev, Boris and Shvetsov, Roman and Efremova, Natalia and Kuharenko, Artem},
  journal={arXiv preprint arXiv:1711.04598},
  year={2017}
}
```


提取维度为1024的fc6 CNN特征用于视觉
音频使用openSmile 提取 1582维特征
本文无元素数据集 提供下载的是提取的特征 
