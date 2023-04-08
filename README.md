# Low-Rank Embedded Network for Sample-Free Hyperspectral Anomaly Detection
**Abstract：** <br />
Hyperspectral anomaly detection (HAD) is a challenging task because it explores the intrinsic structure of complex high-dimensional signals without any samples at training time. Deep neural networks (DNNs) can dig out the underlying distribution of hyperspectral data but are limited by the labeling of large-scale hyperspectral datasets, especially the low spatial resolution of hyperspectral data, which makes labeling more difficult. To tackle this problem while ensuring the detection performance, we present an unsupervised low-rank embedded network (LREN) in this paper. LREN is a joint learning network in which the latent representation is specifically designed for HAD, rather than merely as a feature input for the detector. And it searches the lowest rank representation based on a representative and discriminative dictionary in the deep latent space to estimate the residual efficiently. Considering the physically mixing properties in hyperspectral imaging, we develop a trainable density estimation module based on Gaussian mixture model (GMM) in the deep latent space to construct a dictionary that can better characterize the complex hyperspectral images (HSIs). The closed-form solution of the proposed low-rank learner surpasses existing approaches on four real hyperspectral datasets with different anomalies. We argue that this unified framework paves a novel way to combine feature extraction and anomaly estimation-based methods for HAD, which intends to learn the underlying representation tailored for HAD without the prerequisite of manually labeled data. Code available at https://github.com/xdjiangkai/LREN. <br />
**Code & Model:** https://github.com/xdjiangkai/LREN <br />
**Paper:** https://doi.org/10.1609/aaai.v35i5.16536
<br />
If our code is helpful to you, please cite:
```
@inproceedings{jiang2021lren,
  title={LREN: Low-rank embedded network for sample-free hyperspectral anomaly detection},
  author={Jiang, Kai and Xie, Weiying and Lei, Jie and Jiang, Tao and Li, Yunsong},
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence},
  volume={35},
  number={5},
  pages={4139--4146},
  year={2021}
}
```
