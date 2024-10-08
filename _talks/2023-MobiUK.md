---
title: "Efficient Mobile Network Drive Testing with Deep Generative Modeling"
collection: talks
type: "Conference"
permalink: /talks/2023-MobiUK 
venue: "MobiUK 2023"
date: 2023-07-03
location: "Management School, Lancaster University, UK"
excerpt: "The main goal of drive testing is to assess and optimize mobile network coverage, capacity, and quality
of service (QoS) through measurement. This involves collecting field measurements in a controlled manner by
driving or walking in a target scenario. Drive testing continues to play a key role in mobile network optimization
for operators. The principal concern with traditional drive testing is that it requires manual effort to obtain
measurements, making it costly and time-consuming. Several measurement tools are available to perform drive
or walk testing..."
---

[Note of Talk](https://mobiuk.org/2023/abstract/S4_P3_Sun_DriveTesting.pdf)

The main goal of drive testing is to assess and optimize mobile network coverage, capacity, and quality of service (QoS) through measurement. This involves collecting field measurements in a controlled manner by driving or walking in a target scenario. Drive testing continues to play a key role in mobile network optimization for operators. The principal concern with traditional drive testing is that it requires manual effort to obtain measurements, making it costly and time-consuming. Several measurement tools are available to perform drive or walk testing. One alternative approach called virtual drive testing (VDT) is limited to device/equipment testing, whereas other alternative approaches involving user device based measurement collection via 3GPP minimization of drive tests (MDT) feature or via crowdsourcing are hindered by insufficient incentives for user
participation and privacy concerns. Motivated by the above, we propose GenDT [1], a novel approach to make mobile network drive testing efficient that is driven by a tailored deep generative model to effectively mimic drive testing. Specifically, the deep generative model design at the core of GenDT aims to synthesize high-fidelity drive testing data, i.e., time series of radio network key performance indicators (KPIs) for a given drive test trajectory. The training of GenDT relies on a relatively small amount of real-world drive test measurement data, along with corresponding and easily accessible network and environment context data. Through this, GenDT learns the relationship between context and radio network KPIs as they vary over time. As a result, a trained GenDT model can subsequently be relied on to generate time series for different KPIs for new drive test routes (trajectories) without having to collect field measurements.
