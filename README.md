# Rethinking the Metric in Few-shot Learning: From an Adaptive Multi-Distance Perspective
This is an official implementation in PyTorch of AMTNet, which is accepted by ACMMM-2022.

The full code will be released soon.

<p align="center">
  <img src="doc/AMTNet.png" width="100%"/></a>
</p>

<p align="center">
  <img src="doc/AMM.png" width="100%"/></a>
</p>



## Abstract

Few-shot learning problem focuses on recognizing unseen classes given a few labeled images. In recent effort, more attention is paid to fine-grained feature embedding, ignoring the relationship among different distance metrics. In this paper, for the first time, we investigate the contributions of different distance metrics, and propose an adaptive fusion scheme, bringing significant improvements in few-shot classification. We start from a naive baseline of confidence summation and demonstrate the necessity of exploiting the complementary property of different distance metrics. By finding the competition problem among them, built upon the baseline, we propose an Adaptive Metrics Module (AMM) to decouple metrics fusion into metric-prediction fusion and metric-losses fusion. The former encourages mutual complementary, while the latter alleviates metric competition via multi-task collaborative learning. Based on AMM, we design a few-shot classification framework AMTNet, including the AMM and the Global Adaptive Loss (GAL), to jointly optimize the few-shot task and auxiliary self-supervised task, making the embedding features more robust. In the experiment, the proposed AMM achieves 2% higher performance than the naive metrics fusion module, and our AMTNet outperforms the state-of-the-arts on multiple benchmark datasets.



## Citation

If you use this code for your research, please cite our paper:
```
@inproceedings{lai2022rethinking,
  title={Rethinking the Metric in Few-shot Learning: From an Adaptive Multi-Distance Perspective},
  author={Jinxiang Lai, Siqian Yang, Guannan Jiang, Xi Wang, Yuxi Li, Zihui Jia, Xiaochen Chen, Jun Liu, Bin-Bin Gao, Wei Zhang, Yuan Xie, Chengjie Wang},
  booktitle={Proceedings of the 30th ACM International Conference on Multimedia},
  pages={4021--4030},
  year={2022}
}
```

