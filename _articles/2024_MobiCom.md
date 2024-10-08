---
title: "SpotLight: Accurate, Explainable and Efficient Anomaly Detection for Open RAN"
category: Research Paper
permalink: /articles/2024_MobiCom
excerpt: "The Open RAN architecture, with disaggregated and virtualized RAN functions communicating over standardized interfaces, promises a diversified and multi-vendor RAN ecosystem. However, these same features contribute to increased operational complexity, making it highly challenging to troubleshoot RAN related performance issues and failures. Tackling this challenge requires a dependable, explainable anomaly detection method that Open RAN is currently lacking. To address this problem, we introduce SpotLight, a tailored system archtecture with a distributed deep generative modeling based method running across the edge and cloud. SpotLight takes in a diverse, fine grained stream of metrics from the RAN and the platform, to continually detect and localize anomalies. It introduces a novel multi-stage generative model to detect potential anomalies at the edge using a lightweight algorithm, followed by anomaly confirmation and an explainability phase at the cloud, that helps identify the minimal set of KPIs that caused the anomaly. We evaluate SpotLight using the metrics collected from an enterprise-scale 5G Open RAN deployment in an indoor office building. Our results show that compared to a range of baseline methods, SpotLight yields significant gains in accuracy (13% higher F1 score), explainability (2.3 − 4× reduction in the number of reported KPIs) and efficiency (4 − 7× bandwidth reduction)."
venue: "ACM MobiCom'24"
date: 2024-05-15
---

Oral Presentation on MobiCom'24 [Program](https://www.sigmobile.org/mobicom/2024/program.html)
