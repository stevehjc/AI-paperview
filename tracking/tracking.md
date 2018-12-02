
# Visual Object Tracking:单目标跟踪资源整理

[TOC]

## Dataset


### 1. Visual Tracker Benchmark(OTB)

- [OTB官网](http://cvlab.hanyang.ac.kr/tracker_benchmark/index.html)

- 常用数据集OTB-50，OTB-100；CVPR2013 论文[Online Object Tracking: A Benchmark](http://faculty.ucmerced.edu/mhyang/papers/cvpr13_benchmark.pdf)提出了这个数据集，并且将当时的算法和之前的算法在这个数据集上做了对比实验，给出了benchmark结果。之后的这几年，这个数据集也成为后来的新算法必用的数据集。
- 标签格式:[左上角坐标x,y,w,h]


### 2. Visual Object tracking(VOT)
- [VOT官网](http://www.votchallenge.net/)
- 2013年~2018年每年都举办The VOT challenges
- VOT标签格式：四个点坐标，Box不是平行于坐标轴的
- [VOT2018result](http://www.votchallenge.net/vot2018/results.html)
- [VOT2017result](http://www.votchallenge.net/vot2017/results.html)

## Tracking参考资源

- github上一个benchmark result:可以用来顺藤摸瓜，看论文

https://github.com/foolwood/benchmark_results


## VOT challenge evaluation toolkit
- [code-matlab](https://github.com/votchallenge/vot-toolkit)

## 看过的一些Papers和Code整理

### DaSiamRPN
[ECCV2018,Distractor-aware Siamese Networks for Visual Object Tracking](http://arxiv.org/abs/1808.06048)
- [Code](https://github.com/foolwood/DaSiamRPN)
- 代码使用Pytorch,支持下载训练模型,不包含训练代码


### SiamPPN
[CVPR2018,High Performance Visual Tracking With Siamese Region Proposal Network](http://openaccess.thecvf.com/content_cvpr_2018/html/Li_High_Performance_Visual_CVPR_2018_paper.html)


### ECO
[CVPR2017,ECO: Efficient convolution operators for tracking](https://arxiv.org/pdf/1611.09224.pdf)
- [Code](https://github.com/martin-danelljan/ECO)
- 代码使用MATLAB


### cfnet
[CVPR2017,End-to-end representation learning for Correlation Filter based tracking](http://openaccess.thecvf.com/content_cvpr_2017/html/Valmadre_End-To-End_Representation_Learning_CVPR_2017_paper.html)
- [Code-Matlab](https://github.com/bertinetto/cfnet),支持训练,评估

- [Code-tf](https://github.com/torrvision/siamfc-tf),不支持训练
