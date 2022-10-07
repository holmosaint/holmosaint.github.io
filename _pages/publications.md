---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## 2022
-  **Sheng, K.**, Zhang, S., Beau, M., Qu, P., Yang, L., Liu, X., He, L., Ma, L., \& Du, K. (2022). Domain Adaptive Neural Inference for Neurons, Microcircuits and Networks. *bioRxiv*.
- Shi, R., Wang, W., Li, Z., He, L., **Sheng, K.**, Ma, L., Du, K., Jiang, T., and Huang, T. (2022) U-RISC: An Annotated Ultra-High-Resolution Electron Microscopy Dataset Challenging the Existing Deep Learning Algorithms. *Front. Comput. Neurosci.* 16:842760. doi: [10.3389/fncom.2022.842760](10.3389/fncom.2022.842760)
- Su, L., Wang, W., **Sheng, K.**, Liu, X., Du, K., Tian, Y., and Ma, L. (2022) Siamese Network-Based All-Purpose-Tracker, a Model-Free Deep Learning Tool for Animal Behavioral Tracking. *Front. Behav. Neurosci.* 16:759943. doi: [10.3389/fnbeh.2022.759943](10.3389/fnbeh.2022.759943) (\* equally contributed)

## 2021
- **Sheng, K.**, Qu, P., Yang, L., Liu, X., He, L., Ma, L., and Du, K. (2021). A General LSTM-based Deep Learning Method for Estimating Neuronal Models and Inferring Neural Circuitry. *bioRxiv*.

## 2020
- Shi, R., Wang, W., Li, Z., He, L., **Sheng, K.**, Ma, L., ... and Huang, T. (2020). Human Perception-based Evaluation Criterion for Ultra-high Resolution Cell Membrane Segmentation. *arXiv preprint arXiv:2010.08209*.

- Zheng, S., Liang, Y., Wang, S., Chen, R., and **Sheng, K.**. (2020, March) FlexTensor: An Automatic Schedule Exploration and Optimization Framework for Tensor Computation on Heterogeneous System. In *Proceedings of the Twenty-Fifth International Conference on Architectural Support for Programming Languages and Operating Systems* (pp. 859-873) doi: [10.1145/3373376.3378508](10.1145/3373376.3378508)

<div style='display: none'>
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
</div>