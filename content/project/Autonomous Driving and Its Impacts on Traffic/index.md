---
title: Autonomous Driving and Its Impacts on Traffic
summary: Investigate the driving behavior and stability of autonomous vehicles. Not only explore how AVs operate individually but also how they influence traffic flow collectively.
 
date: 2021-09-01
# external_link: https://github.com/pandas-dev/pandas
tags:
  - Autonomous driving
  - Mixed traffic flow
---
<div align="justify">Understanding the impacts of autonomous vehicles (AVs) on traffic requires bridging the gap between vehicle-level behaviors and system-level outcomes. My research approaches this challenge through two complementary studies: the stability of AV car-following dynamics and the fundamental diagram of mixed traffic flow.</div>

<h3> String stability analysis of NN-based car-following model</h3>
<img src="stability.svg" alt="String stability analysis of NN-based car-following model">
<div align="justify">The first line of work addresses <b>string stability</b>. Stability is critical because even minor fluctuations in car-following behavior can propagate and amplify, creating stop-and-go waves that degrade traffic efficiency. While traditional analytical models have been widely studied, no theoretical framework existed for analyzing the string stability of neural network–based car-following models, which are increasingly used to capture realistic AV behavior.<br>
<img src="EADC.svg" alt="Overall framework">
To fill this gap, I developed the EADC framework (Estimation–Approximation–Derivation–Calculation), which derives stability criteria for both feedforward and recurrent neural network models. Validated on representative NN-based models, the framework demonstrates consistency between theoretical and simulation results, establishing the first rigorous method for assessing the stability of AI-driven vehicle behavior.</div>

<h3> Stochastic Fundamental Diagram modeling for mixed traffic</h3>
<img src="Mixed_SFD.svg" alt="A data-driven framework for stochastic fundamental diagram modeling of mixed traffic">
<div align="justify">The second line of work focuses on the <b>Stochastic Fundamental Diagram (SFD) for mixed traffic</b>. Current AV impact studies often oversimplify traffic dynamics or ignore stochasticity, limiting their realism. To overcome this, I proposed a data-driven probabilistic modeling framework that learns car-following interactions for all leader–follower types (AV–AV, AV–HV, HV–AV, HV–HV) using mixture density networks. By modeling platoons as Markov chains, the framework derives the SFD from trajectory data, validated against NGSIM and Waymo datasets. Results show that higher AV penetration decreases mean capacity and critical density while reducing capacity uncertainty, highlighting the conservative yet stabilizing effects of current AVs.</div>

<h3> Research Impact</h3>
<div align="justify">Together, these studies reveal how AVs influence traffic from the perspective of stability and capacity: string stability analysis ensures the reliability of AI-based AV behavior, while SFD modeling quantifies the systemic effects of AV penetration. My contributions establish new theoretical and data-driven foundations for assessing AV impacts, with implications for both traffic management strategies and policy-making in the era of mixed traffic.</div>

<h3> References</h3>
<div align="justify">
<cite> 
<ul>
<li><b>Zhang, X.</b>, Sun, Jie, Zheng, Z., Sun, Jian, 2024. On the string stability of neural network-based car-following models: A generic analysis framework. Transportation Research Part C: Emerging Technologies 160, 104525.</li> 
<li><b>Zhang, X.</b>, Yang, K., Sun, Jie, Sun, Jian, 2025. Stochastic fundamental diagram modeling of mixed traffic flow: A data-driven approach. Transportation Research Part C: Emerging Technologies 179, 105279.</li>
</ul>
</cite>
</div>
<!-- Flexible and powerful data analysis / manipulation library for Python, providing labeled data structures. -->

<!--more-->
