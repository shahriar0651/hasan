---
title: "CANShield: Deep-Learning-Based Intrusion Detection Framework for Controller Area Networks at the Signal Level"
collection: publications
permalink: /publication/2023-08-23-Paper_CANtropy
excerpt: 'This paper proposed a deep learning-based signal level intrusion detection framework for the controller area network (CAN) bus.'
date: 2023-08-23
venue: 'IEEE Internet of Things Journal'
# slidesurl: 'http://shahriar0651.github.io/files/slides2.pdf'
paperurl: 'http://shahriar0651.github.io/files/paper_2023_CANShield.pdf'
citation: 'Shahriar, M. H., Xiao, Y., Moriano, P., Lou, W., & Hou, Y. T. (2023). CANShield: Deep Learning-Based Intrusion Detection Framework for Controller Area Networks at the Signal-Level. IEEE Internet of Things Journal.'
---

Modern vehicles rely on a fleet of electronic control units (ECUs) connected through controller area network (CAN) buses for critical vehicular control. With the expansion of advanced connectivity features in automobiles and the elevated risks of internal system exposure, the CAN bus is increasingly prone to intrusions and injection attacks. As ordinary injection attacks disrupt the typical timing properties of the CAN data stream, rule-based intrusion detection systems (IDS) can easily detect them. However, advanced attackers can inject false data to the signal/semantic level, while looking innocuous by the pattern/frequency of the CAN messages. The rule-based IDS, as well as the anomaly-based IDS, are built merely on the sequence of CAN messages IDs or just the binary payload data and are less effective in detecting such attacks. Therefore, to detect such intelligent attacks, we propose CANShield, a deep learning-based signal level intrusion detection framework for the CAN bus. CANShield consists of three modules: 1) a data preprocessing module that handles the high-dimensional CAN data stream at the signal level and parses them into time series suitable for a deep learning model; 2) a data analyzer module consisting of multiple deep autoencoder (AE) networks, each analyzing the time-series data from a different temporal scale and granularity; and 3) finally an attack detection module that uses an ensemble method to make the final decision. Evaluation results on two high-fidelity signal-based CAN attack data sets show the high accuracy and responsiveness of CANShield in detecting advanced intrusion attacks.