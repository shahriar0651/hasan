---
title: "Intrusion Detection Systems (IDS) for Controller Area Networks (CAN) Bus"
excerpt: "Our research focuses on improving the security of Controller Area Networks (CAN) in modern vehicles, which are increasingly dependent on interconnected electronic control units (ECUs) for critical functions. The CAN protocol, designed for reliability and efficiency, lacks built-in security measures, making it vulnerable to sophisticated cyberattacks that exploit these gaps. Traditional IDS methods, which monitor timing and message sequences, are inadequate against advanced attacks that manipulate signal semantics. Our work addresses these challenges by developing detection systems that can identify such subtle intrusions, enhancing the overall security of vehicular networks.
<br/><img src='/images/workflow_canshield.jpg'>"
collection: portfolio
---

Our research is dedicated to advancing the security of Controller Area Networks (CAN) in modern vehicles, which are increasingly reliant on interconnected electronic control units (ECUs) for essential functions such as braking, steering, and engine control. While the CAN protocol was originally designed with a focus on reliability and efficiency, it lacks inherent security measures, leaving vehicular networks vulnerable to cyberattacks. As vehicles become more connected, this vulnerability poses a significant risk, as attackers can potentially exploit these security gaps to disrupt vehicle operations, leading to severe and even life-threatening consequences.

Traditional Intrusion Detection Systems (IDS) for CAN buses have primarily focused on rule-based or anomaly-based approaches that monitor timing properties or message sequences within the CAN data stream. While these methods can effectively detect basic attacks that disrupt these properties, they fall short when faced with more sophisticated intrusions. Advanced attackers can manipulate the signal or semantic level of CAN messages, injecting malicious data that appears normal in terms of timing and frequency but alters the underlying signal values. This subtlety allows the attack to evade detection by conventional IDS, posing a new challenge for vehicular network security.

The complexity and sophistication of modern cyber threats necessitate the development of advanced IDS capable of analyzing CAN data at a finer, signal-level granularity. However, this pursuit is met with several key challenges:

- **High Dimensionality and Complexity**: The CAN bus generates a continuous stream of high-dimensional time-series data, which is challenging to parse, analyze, and interpret effectively.
- **Scalability and Generalization**: Deep learning-based IDS must be designed to scale and generalize across various attack scenarios, which often requires significant optimization and careful model selection.
- **Real-time Detection**: Given the critical nature of vehicular systems, IDS must be both accurate and responsive, capable of detecting and mitigating threats in real-time to prevent catastrophic outcomes.

**Key Contributions**

1. **CANShield** [1]: We developed CANShield, a deep learning-based IDS framework that detects signal-level intrusions within CAN buses. CANShield employs a multi-module system, including deep autoencoders and an ensemble detection method, to identify sophisticated attacks that evade traditional IDS by manipulating signal semantics without altering the overall pattern of CAN messages. This framework has demonstrated high accuracy and responsiveness in detecting advanced attacks on high-fidelity datasets, contributing to the state-of-the-art in vehicular network security.
<br/><img src='/images/workflow_canshield.jpg'>


2. **CANtropy** [2]: We introduced CANtropy, a lightweight IDS that leverages manual feature engineering to extract critical temporal and statistical features from CAN signals. CANtropy utilizes a principal component analysis-based anomaly detection model to ensure scalability and effectiveness in detecting a broad spectrum of cyberattacks. This approach has outperformed existing deep learning-based IDS solutions, achieving excellent generalization and an AUROC score of 0.992 on the SynCAN dataset.
<br/><img src='/images/workflow_cantropy.jpg'>

**Future Directions**

To develop efficient, robust, and scalable Intrusion Detection Systems (IDS) for vehicular networks, our future research will focus on:
- **Adversarial Resilience**: Enhancing IDS robustness against adversarial attacks to ensure resilience in evolving cyber threats.
- **Cross-Domain Applications**: Extending signal-level intrusion detection to other modalities such as Vehicle-to-Everything (V2X) , multi-modal sensors such as camera, lidar, radar, etc.
- **Scalable and Explainable AI**: Creating scalable and interpretable IDS models to build trust and facilitate adoption in critical infrastructure.

These efforts will advance vehicular network security, ensuring the safety and reliability of next-generation vehicles and other critical systems.

**References**
- [1] Shahriar, M. H., Xiao, Y., Moriano, P., Lou, W., & Hou, Y. T. (2023). CANShield: Deep Learning-Based Intrusion Detection Framework for Controller Area Networks at the Signal-Level. IEEE Internet of Things Journal.
- [2] Shahriar, M. H., Lou, W., & Hou, Y. T. (2023). CANtropy: Time series feature extraction-based intrusion detection systems for controller area networks. In Proc. of Symp. on Vehicles Security and Privacy (VehicleSec) (pp. 1-8). 
