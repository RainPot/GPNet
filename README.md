# GPNet: Gated pyramid network for semantic segmentation

This is the code for the Semantic Segmentation.

- Train
`train.py`
- Eval
`eval_multiscale.py`
- Test
`test.py`

## Citation

```bibtex
@article{ZHANG2021107940,
title = {GPNet: Gated pyramid network for semantic segmentation},
journal = {Pattern Recognition},
volume = {115},
pages = {107940},
year = {2021},
issn = {0031-3203},
doi = {https://doi.org/10.1016/j.patcog.2021.107940},
url = {https://www.sciencedirect.com/science/article/pii/S0031320321001278},
author = {Yu Zhang and Xin Sun and Junyu Dong and Changrui Chen and Qingxuan Lv},
keywords = {Deep learning, Semantic segmentation, Context embedding, Gated mechanism, Attention},
abstract = {Semantic segmentation is a challenging task which requires both solid unanimous global context and rich spatial information. Recent methods ignore adaptively capturing of valid feature. The lack of useful multi-scale information filtering hinders further explicit feature generation. In this paper, we develop a novel network named GPNet, which can densely capture and filter the multi-scale information in a gated and pair-wise manner. Specifically, a Gated Pyramid Module (GPM) is designed to incorporate dense and growing receptive fields from both low-level and high-level features. In GPM we build a gated path to select useful context among multi-scale information. Moreover, a Cross-Layer Attention Module (CLAM) is proposed to reuse the context information from shallow layers to guide the deep features. Comprehensive experimental evaluations are conducted on popular semantic segmentation benchmarks including Cityscapes and ADE20K. Our GPNet achieves the mIoU score of 82.5% and 45.81% on Cityscapes test set and ADE20K validation set, respectively, which are the new state-of-the-art results using ResNet-101 as the backbone.}
}
```
