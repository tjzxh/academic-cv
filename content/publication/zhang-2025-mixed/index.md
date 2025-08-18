---
title: 'On the stochastic fundamental diagram: A general micro-macroscopic traffic
  flow modeling framework'
authors:
- Xiaohui Zhang
- Kaidi Yang
- Jie Sun
- Jian Sun
date: '2025-01-01'
publishDate: '2025-08-17T03:16:35.726983Z'
publication_types:
- article-journal
publication: '*Transportation research part C: emerging technologies*'

abstract: The integration of automated vehicles (AVs) into existing traffic of human-driven vehicles (HVs) poses significant challenges in modeling and optimizing mixed traffic flow. Existing research on the impacts of AVs often neglects the stochastic nature of traffic flow that gets further complicated by the introduction of AVs, and mainly relies on unrealistic assumptions, such as oversimplified headway or specific car-following (CF) models. The under-utilization of empirical AV datasets further exacerbates these issues, raising concerns about the realism and applicability of existing findings. To address these limitations, this paper presents a novel data-driven framework to model the stochastic fundamental diagram (SFD) of mixed traffic flow using AV trajectory datasets. Specifically, we learn the CF behavior of different leader–follower pairs (HV following AV, HV following HV, AV following HV, AV following AV) from data, unified by a conditional distribution, using the mixture density network (MDN). By formulating the platoon as a joint distribution through Markov chain modeling and incorporating all possible platoon arrangements, we then derive the SFD of mixed traffic flow. Using the NGSIM I-80 dataset, which enables aggregating the empirical fundamental diagram, we validate the proposed framework by demonstrating high consistency with the empirical result. We then apply the framework to the Waymo dataset to evaluate the impact of real-world AVs on traffic flow. The results indicate that larger AV penetration rates lead to decreased mean capacity and critical density while reducing capacity uncertainty, due to the conservative yet stable behavior of current AVs. Overall, this work establishes a general probabilistic modeling framework for mixed traffic flow, enabling the input of real-world AV trajectory datasets and output of the SFD under given AV penetration rates and AV spatial distributions. The proposed framework further facilitates assessing and comparing mixed traffic management strategies, with significant implications for future traffic system design and policy-making.

# Summary. An optional shortened abstract.
summary: A data-driven framework to model the impacts of AV on traffic flow.

tags:
  - Impacts of AV on traffic

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
url_code: 'https://github.com/tjzxh/SFD-modeling-of-mixed-traffic'
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
