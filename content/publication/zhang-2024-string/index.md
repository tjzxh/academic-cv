---
title: 'On the string stability of neural network-based car-following models: A generic
  analysis framework'
authors:
- Xiaohui Zhang
- Jie Sun
- Zuduo Zheng
- Jian Sun
date: '2024-01-01'
publishDate: '2025-08-17T03:16:35.721076Z'
publication_types:
- article-journal
publication: '*Transportation research part C: emerging technologies*'
abstract: String stability plays a crucial role in regulating traffic flow, as traffic oscillation can be triggered by string instability in the car-following (CF) behavior. Although studies over the past decades have provided various methods for analyzing string stability of analytical CF models, no studies have focused on neural network (NN) based CF models despite the fact that these models have exhibited remarkable performance in learning realistic driving behavior in the recent literature. This paper fills this gap by proposing a generic theoretical framework for analyzing the string stability of NN-based CF models through an Estimation-Approximation-Derivation-Calculation process (referred to as EADC framework). Within the framework, we first estimate the steady states of NN-based CF models by solving the corresponding optimization model and obtain the smooth approximation of the NN-based models for linearization, based on which the transfer function is constructed. We then derive the general stability criteria for two commonly used classes of NN in CF modeling, i.e., feedforward NN-based CF models with basic input and recurrent NN-based CF models with multi-step historical information. The string stability is thus obtained by calculating the partial derivatives through the automatic differentiation method. As two case studies, we apply the proposed stability analysis framework on two typical NN-based CF models, the Mo-MLP model (Mo et al., 2021) and the Huang-LSTM model (Huang et al., 2018), and obtained the complete consistency between the theoretical results and the simulation results for both models, which demonstrates the soundness of the proposed EADC framework. Moreover, we discuss the applicability of the proposed EADC stability analysis framework in the emerging era of connected and autonomous vehicles and artificial intelligence.

# Summary. An optional shortened abstract.
summary: A generic framework for theoretical string stability analysis of NN-based models.

tags:
  - Traffic flow theory
  - Artificial Intelligence in Transportation Research

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: 'content/publication/zhang-2025-sfd/zhang-2025-sfd.pdf'
url_code: 'https://github.com/tjzxh/EADC'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
url_poster: ''
url_project: ''
url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Overview'
  focal_point: ''
  preview_only: false
---
