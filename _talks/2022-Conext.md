---
title: "GenDT: Mobile Network Drive Testing Made Efficient with Generative Modeling"
collection: talks
type: "Conference"
permalink: /talks/2022-Conext 
venue: "ACM CoNEXT 2022"
date: 2022-12-02
location: "Rome, Italy"
excerpt: "Drive testing continues to play a key role in mobile network optimization for operators but its high cost is a big concern. Alternative approaches like virtual drive testing (VDT) target device testing in the lab whereas MDT or crowdsourcing based approaches are limited by the incentives users have to participate and contribute measurements. With the aim of augmenting drive testing and significantly reducing its cost, we propose GenDT, a novel deep generative model that synthesizes high-fidelity time series of key radio network key performance indicators (KPIs)..."
---
[Paper Download](https://dl.acm.org/doi/abs/10.1145/3555050.3569124)

Abstract: Drive testing continues to play a key role in mobile network optimization for operators but its high cost is a big concern. Alternative approaches like virtual drive testing (VDT) target device testing in the lab whereas MDT or crowdsourcing based approaches are limited by the incentives users have to participate and contribute measurements. With the aim of augmenting drive testing and significantly reducing its cost, we propose GenDT, a novel deep generative model that synthesizes high-fidelity time series of key radio network key performance indicators (KPIs). The training of GenDT relies on a relatively small amount of real-world measurement data along with corresponding and easily accessible network and environment context data. Through this, GenDT learns the relationship between context and radio network KPIs as they vary over time, and therefore trained GenDT model can subsequently be relied on to generate time series for different KPIs for new drive test routes (trajectories) without having to collect field measurements. GenDT represents an initial attempt at enabling efficient drive testing via generative modeling. Evaluations with real-world mobile network drive testing measurement datasets from two countries demonstrate that GenDT can synthesize significantly more dependable data than a range of baselines. We further show that GenDT has the potential to significantly reduce the drive testing related measurement effort, and that GenDT-generated data yields similar results to that with real data in the context of two downstream use cases - QoE prediction and handover analysis.
