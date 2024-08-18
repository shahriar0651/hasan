---
title: "CANtropy: Time Series Feature Extraction-Based Intrusion Detection Systems for Controller Area Networks"
collection: publications
permalink: /publication/2023-2-27-Paper_CANtropy
excerpt: 'This paper proposed a manual feature engineeringbased lightweight IDS for controller area network (CAN) bus.'
date: 2023-02-27
venue: 'Symposium on Vehicles Security and Privacy (VehicleSec)'
# slidesurl: 'http://shahriar0651.github.io/files/slides2.pdf'
paperurl: 'http://shahriar0651.github.io/files/paper_2023_CANtropy.pdf'
citation: 'Shahriar, M. H., Lou, W., & Hou, Y. T. (2023). CANtropy: Time series feature extraction-based intrusion detection systems for controller area networks. In Proc. of Symp. on Vehicles Security and Privacy (VehicleSec) (pp. 1-8).'
---

A controller area network (CAN) connects dozens of electronic control units (ECUs), ensuring reliable and efficient data transmission. Because of the lack of security features of CAN protocol, in-vehicle networks are susceptible to a wide spectrum of threats, from simple injections at high frequencies to sophisticated masquerade attacks that target individual sensor values (signals). Hence, advanced analysis of the multidimensional time-series data is needed to learn the complex patterns of individual signals and their mutual dependencies. Although deep learning (DL)-based intrusion detection systems (IDS) have shown potential in such domain, they tend to suffer from poor generalization as they need optimization at every component. To detect such advanced CAN attacks, we propose CANtropy, a manual feature engineeringbased lightweight CAN IDS. For each signal, CANtropy explores a comprehensive set of features from both temporal and statistical domains and selects only the effective subset of features in the detection pipeline to ensure scalability. Later, CANtropy uses a lightweight unsupervised anomaly detection model based on principal component analysis, to learn the mutual dependencies of the features and detect abnormal patterns in the sequence of CAN messages. The evaluation results on the advanced SynCAN dataset show that CANtropy provides a comprehensive defense against diverse types of cyberattacks with an average AUROC score of 0.992, and outperforms the existing DL-based baselines.