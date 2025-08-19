---
title: Simultaneous modeling of car-following and lane-changing behaviors using deep
  learning
authors:
- Xiaohui Zhang
- Jie Sun
- Xiao Qi
- Jian Sun
date: '2019-01-01'
publishDate: '2025-08-17T03:16:35.689660Z'
publication_types:
- article-journal
publication: '*Transportation research part C: emerging technologies*'
abstract: Car-following (CF) and lane-changing (LC) behaviors are two basic movements in traffic flow which are generally modeled separately in the literature, and thus the interaction between the two behaviors may be easily ignored in separated models and lead to unrealistic traffic flow description. In this paper, we adopt a deep learning model, long short-term memory (LSTM) neural networks, to model the two basic behaviors simultaneously. By only observing the position information of the six vehicles surrounding the subject vehicle, the LSTM can extract the significant features that influence the CF and LC behaviors automatically and predict the vehicles behaviors with time-series data and memory effects. In addition, we propose a hybrid retraining constrained (HRC) training method to further optimize the LSTM model. With the I-80 trajectory data of NGSIM dataset we train and test the HRC LSTM model, while the results show that HRC LSTM model can accurately estimate CF and LC behaviors simultaneously with low longitudinal trajectories error and high LC prediction accuracy compared with the classical models. We also evaluate the transferability of the proposed model with the US101 dataset and a good transferability result is obtained as well.

# Summary. An optional shortened abstract.
summary: The hybrid retraining constrained (HRC) LSTM is proposed to model the Car following (CF) and Lane Changing (LC) behaviors simultaneously.

tags:
- Artificial Intelligence in Transportation Research

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: 'content/publication/zhang-2025-sfd/zhang-2025-sfd.pdf'
url_code: 'https://github.com/tjzxh/HRC-LSTM'
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
