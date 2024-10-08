---
title: "SpotLight -- An Open RAN Anomaly Detection and Identification System"
category: Demo
permalink: /articles/2024-03-01-MobiCom-Demo
excerpt: "A real-world implementation of Spotlight. Corresponds to our paper on the main conference of MobiCom'24."
date: 2024-03-01
venue: ACM MobiCom'24 Demo
---
This is the demo of our MobiCom paper: Spotlight.

The dataset will be open-source soon. To our knowledge, this will be the first open-source dataset for Open RAN that provides comprehensive measurements spanning from the physical layer to CPU thread-level performance.

Abstract: The Open RAN architecture, featuring disaggregated and virtualized RAN functions communicating over standardized interfaces, promises a diverse, multi-vendor ecosystem. However, these features also increase operational complexity, complicating the troubleshooting of RAN performance issues and failures. Addressing this challenge requires a reliable, explainable anomaly detection method, which Open RAN currently lacks. To address this problem, we have developed SpotLight, a tailored distributed deep learning method running across the edge and cloud. SpotLight continuously detects and localizes anomalies by analyzing a diverse, fine-grained stream of metrics from the RAN and platform. It employs a novel multi-stage generative model to identify potential anomalies at the edge using a lightweight algorithm, followed by anomaly confirmation and an explainability phase in the cloud, which pinpoints the minimal set of KPIs responsible for the anomaly. In this demo, using a carrier-grade indoor Open RAN testbed with configurable anomaly event generation and replay, we highlight (1) the difficulty of troubleshooting problems in Open RAN and (2) accurate, efficient, and explainable on- line anomaly detection with SpotLight and corresponding visualization in comparison with prior art.

