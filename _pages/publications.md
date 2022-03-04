---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## 2022
- Su, L.\*, Wang, W.\*, **Sheng, K.**, Liu, X., Du, K., Tian, Y., & Ma, L. Siamese Network-Based All-Purpose-Tracker, a Model-Free Deep Learning Tool for Animal Behavioral Tracking. Frontiers in Behavioral Neuroscience, 48. (\* equally contributed)

## 2021
- **Sheng, K.**, Qu, P., Yang, L., Liu, X., He, L., Ma, L., & Du, K. (2021). A General LSTM-based Deep Learning Method for Estimating Neuronal Models and Inferring Neural Circuitry. *bioRxiv*.
-  Shi, R., Wang, W., Li, Z., He, L., **Sheng, K.**, Ma, L., ... & Huang, T. (2021). U-RISC: an ultra-high-resolution EM dataset challenging existing deep learning algorithms. *bioRxiv*.

## 2020
- Shi, R., Wang, W., Li, Z., He, L., **Sheng, K.**, Ma, L., ... & Huang, T. (2020). Human Perception-based Evaluation Criterion for Ultra-high Resolution Cell Membrane Segmentation. *arXiv preprint arXiv:2010.08209*.

- Zheng, S., Liang, Y., Wang, S., Chen, R., & **Sheng, K.**. (2020, March). FlexTensor: An Automatic Schedule Exploration and Optimization Framework for Tensor Computation on Heterogeneous System. In *Proceedings of the Twenty-Fifth International Conference on Architectural Support for Programming Languages and Operating Systems* (pp. 859-873)

<div style='display: none'>
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
</div>