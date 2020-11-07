# HARNet-On-Device-Human-Activity-Recognition

This repository contains code to our paper, **HARNet: Towards On-Device Incremental Learning using Deep Ensembles on Constrained Devices** which was presented at ACM MobiSys 2018 (2nd International Workshop on Embedded and Mobile Deep Learning, EMDL '18).

## Abstract
Recent advancements in the domain of pervasive computing have seen the incorporation of sensor-based Deep Learning algorithms in Human Activity Recognition (HAR). Contemporary Deep Learning models are engineered to alleviate the difficulties posed by conventional Machine Learning algorithms which require extensive domain knowledge to obtain heuristic hand-crafted features. Upon training and deployment of these Deep Learning models on ubiquitous mobile/embedded devices, it must be ensured that the model adheres to their computation and memory limitations, in addition to addressing the various mobile- and user-based heterogeneities prevalent in actuality. To handle this, we propose HARNet - a resource-efficient and computationally viable network to enable on-line Incremental Learning and User Adaptability as a mitigation technique for anomalous user behavior in HAR. Heterogeneity Activity Recognition Dataset was used to evaluate HARNet and other proposed variants by utilizing acceleration data acquired from diverse mobile platforms across three different modes from a practical application perspective. We perform Decimation as a Down-sampling technique for generalizing sampling frequencies across mobile devices, and Discrete Wavelet Transform for preserving information across frequency and time. Systematic evaluation of HARNet on User Adaptability yields an increase in accuracy by ∼35% by leveraging the model’s capability to extract discriminative features across activities in heterogeneous environments.

Link: https://dl.acm.org/doi/10.1145/3212725.3212728, PDF: https://www.sigmobile.org/mobisys/2018/workshops/deepmobile18/papers/HARNet.pdf

The HHAR dataset used in this paper is available at: https://archive.ics.uci.edu/ml/datasets/Heterogeneity+Activity+Recognition

## Authors
Authors: [Prahalathan Sundaramoorthy](https://prahalath.github.io/), [Gautham Krishna Gudur](https://gauthamkrishna-g.github.io/), Manav Rajiv Moorthy, R. Nidhi Bhandar, Vineeth Vijayaraghavan

## Citation
```
@inproceedings{10.1145/3212725.3212728,
  author = {Sundaramoorthy, Prahalathan and Gudur, Gautham Krishna and Moorthy, Manav Rajiv and Bhandari, R. Nidhi and Vijayaraghavan, Vineeth},
  title = {HARNet: Towards On-Device Incremental Learning Using Deep Ensembles on Constrained Devices},
  year = {2018},
  booktitle = {Proceedings of the 2nd International Workshop on Embedded and Mobile Deep Learning},
  pages = {31–36},
  numpages = {6},
  series = {EMDL '18}
}
```
