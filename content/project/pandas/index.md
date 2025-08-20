---
title: Autonomous Driving and Its Impacts on Traffic
summary: Investigate the driving behavior and stability of autonomous vehicles. Not only explore how AVs operate individually but also how they influence traffic flow collectively.
 
date: 2021-09-01
# external_link: https://github.com/pandas-dev/pandas
tags:
  - Autonomous driving
  - Mixed traffic flow
---
Understanding the impacts of autonomous vehicles (AVs) on traffic requires bridging the gap between vehicle-level behaviors and system-level outcomes. My research approaches this challenge through two complementary studies: the stability of AV car-following dynamics and the fundamental diagram of mixed traffic flow.

### String stability analysis of AV NN-based car-following model

The first line of work addresses **string stability**. Stability is critical because even minor fluctuations in car-following behavior can propagate and amplify, creating stop-and-go waves that degrade traffic efficiency. While traditional analytical models have been widely studied, no theoretical framework existed for analyzing the string stability of neural network–based car-following models, which are increasingly used to capture realistic AV behavior. To fill this gap, I developed the EADC framework (Estimation–Approximation–Derivation–Calculation), which derives stability criteria for both feedforward and recurrent neural network models. Validated on representative NN-based models, the framework demonstrates consistency between theoretical and simulation results, establishing the first rigorous method for assessing the stability of AI-driven vehicle behavior.

### Stochastic Fundamental Diagram modeling for mixed traffic

The second line of work focuses on the **Stochastic Fundamental Diagram (SFD) for mixed traffic**. Current AV impact studies often oversimplify traffic dynamics or ignore stochasticity, limiting their realism. To overcome this, I proposed a data-driven probabilistic modeling framework that learns car-following interactions for all leader–follower types (AV–AV, AV–HV, HV–AV, HV–HV) using mixture density networks. By modeling platoons as Markov chains, the framework derives the SFD from trajectory data, validated against NGSIM and Waymo datasets. Results show that higher AV penetration decreases mean capacity and critical density while reducing capacity uncertainty, highlighting the conservative yet stabilizing effects of current AVs.

Together, these studies reveal how AVs influence traffic from the perspective of stability and capacity: string stability analysis ensures the reliability of AI-based AV behavior, while stochastic FD modeling quantifies the systemic effects of AV penetration. My contributions establish new theoretical and data-driven foundations for assessing AV impacts, with implications for both traffic management strategies and policy-making in the era of mixed traffic.
<!-- Flexible and powerful data analysis / manipulation library for Python, providing labeled data structures. -->

<!--more-->
