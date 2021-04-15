---
title: "fuseGNN: Accelerating Graph Convolutional Neural Network Training on GPGPU"
collection: publications
permalink: /publication/2020-fuseGNN-ICCAD
excerpt: 'A framework powered by customized CUDA kernels for accelerating GNN training on GPGPU'
date: 2020-7-15
venue: '2020 International Conference on Computer Aided Design (ICCAD 2020)'
paperurl: 'https://ieeexplore.ieee.org/document/9256702'
citation: 'Chen, Zhaodong, Mingyu Yan, Maohua Zhu, Lei Deng, Guoqi Li, Shuangchen Li, and Yuan Xie. "fuseGNN: accelerating graph convolutional neural network training on GPGPU." In 2020 IEEE/ACM International Conference On Computer Aided Design (ICCAD), pp. 1-9. IEEE, 2020.'
---
We develop a framework that accelerates GNN training on GPU. It includes a set of CUDA kernels that target on Graph Processing and Aggregation phases in both forward and backward passes. The kernel reduces both execution times and global memory footprint, it enables training GAT on reddit dataset, which was not supported by existing frameworks.

```
@inproceedings{chen2020fusegnn,
  title={fuseGNN: accelerating graph convolutional neural network training on GPGPU},
  author={Chen, Zhaodong and Yan, Mingyu and Zhu, Maohua and Deng, Lei and Li, Guoqi and Li, Shuangchen and Xie, Yuan},
  booktitle={2020 IEEE/ACM International Conference On Computer Aided Design (ICCAD)},
  pages={1--9},
  year={2020},
  organization={IEEE}
}
```
