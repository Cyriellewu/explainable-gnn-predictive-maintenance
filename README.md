# Explainable Dynamic GNNs for Predictive Maintenance in Vehicle Chassis Systems

**ACML 2025 · Proceedings of Machine Learning Research, vol. 304, pp. 878–893**
[Paper (PMLR)](https://proceedings.mlr.press/v304/you25a.html) · [PDF](https://raw.githubusercontent.com/mlresearch/v304/main/assets/you25a/you25a.pdf)

Wu You (first author), Junwei Su, Sirui Zhang, Zhijian Li

## Overview

Commercial vehicle fleets lose money to unexpected breakdowns, and standardized fault codes (SPN/FMI) arrive as irregular, noisy, heavily imbalanced events that conventional time-series models handle poorly.

We propose **NRP-GCN-RF**, a hybrid Node-level Relationship-based Graph Convolutional Network with Random Forest. Fault codes are nodes, co-occurrences are edges, and graph embeddings are combined with spatial and operational features in a tree ensemble (Random Forest / XGBoost). Apriori association-rule mining over SPN-FMI pairs adds interpretable fault patterns that guide feature design and diagnosis.

Built on real-world fleet data from Dongfeng Motor Corporation.

## Results

| Metric | Result |
| --- | --- |
| Overall accuracy | 98.93% |
| Precision on high-cost failures | 60% → 95% |
| Recall | +25% |

## Contents

- `Vehicle_Chassis_Systems-2.pdf`: camera-ready version (ACML 2025)
- `Explainable Dynamic Graph Neural Networks for Predictive Maintenance in Vehicle Chassis Systems.pdf`: earlier version

## Citation

```bibtex
@InProceedings{pmlr-v304-you25a,
  title     = {Explainable Dynamic Graph Neural Networks for Predictive Maintenance in Vehicle Chassis Systems},
  author    = {You, Wu and SU, Junwei and ZHANG, Sirui and Li, Zhijian},
  booktitle = {Proceedings of the 17th Asian Conference on Machine Learning},
  pages     = {878--893},
  year      = {2025},
  volume    = {304},
  series    = {Proceedings of Machine Learning Research},
  publisher = {PMLR},
  url       = {https://proceedings.mlr.press/v304/you25a.html}
}
```
