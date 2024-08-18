---
title: "Robust Misbehavior Detection System (MBDS) For Vehicle-to-Everything (V2X) Communication"
excerpt: "Our research addresses the pressing need for robust misbehavior detection systems (MBDS) in Vehicle-to-Everything (V2X) communication networks, which are essential for modern intelligent transportation systems. V2X networks face significant security challenges due to their open, decentralized nature, which exposes them to advanced adversarial attacks that can evade traditional machine learning-based detection systems. To overcome these issues, we develop **Vehicular GAN (VehiGAN)**, an advanced MBDS leveraging Generative Adversarial Networks (GANs). VehiGAN enhances anomaly detection and offers strong resilience against adversarial manipulations, improving the security and reliability of V2X communications..
<br/><img src='/images/workflow_vehigan.jpg'>"
collection: portfolio
---


Our research is focused on addressing the critical need for robust misbehavior detection systems (MBDS) in Vehicle-to-Everything (V2X) communication networks. V2X technology, which facilitates communication between vehicles and infrastructure to enhance traffic management and road safety, is increasingly becoming integral to modern intelligent transportation systems. However, the open and decentralized nature of V2X networks introduces significant security challenges. Traditional MBDSs often rely on machine learning (ML) techniques, which can struggle with issues such as insufficient and imbalanced training data, dynamic network conditions, and, crucially, vulnerability to adversarial attacks. These attacks can manipulate V2X messages in ways that evade detection by conventional systems, posing serious risks to road safety and network integrity.

To address these challenges, we aim to develop an MBDS that not only excels in detecting a wide range of misbehaviors but also demonstrates robust resistance to adversarial manipulations. Traditional ML-based models, while promising, are susceptible to adversarial attacks that can significantly impair their performance. Our approach leverages Generative Adversarial Networks (GANs) to mitigate these vulnerabilities and enhance detection capabilities. By integrating multiple Wasserstein GANs (WGANs) in an ensemble configuration, we design Vehicular GAN (VehiGAN), which offers both efficient anomaly detection and high resilience against adversarial attacks.

VehiGAN employs a physics-guided data preprocessing technique to optimize feature extraction and model training, improving its ability to detect complex misbehaviors. Our evaluation shows that VehiGAN surpasses existing methods in detecting advanced misbehaviors, particularly those involving multiple fields in V2X messages. It achieves approximately 92% improvement in false positive rates under powerful adaptive attacks and maintains strong performance across various adversarial scenarios. This robust approach makes VehiGAN a leading solution for securing V2X communication networks against evolving cyber threats.
<br/><img src='/images/workflow_vehigan.jpg'>

**Future Directions**
1. **Scalability and Efficiency:** Optimize VehiGAN's computational efficiency and scalability to handle large-scale, real-time data in diverse vehicular environments without performance loss.

2. **Robustness to Novel Adversarial Techniques:** Enhance VehiGAN's resilience by continuously testing and improving its defenses against emerging and sophisticated adversarial attacks.

**References**
- [1] Shahriar, M. H., Ansari, M. R., Monteuuis, J.-P., Chen, C., Petit, J., Hou, Y. T., & Lou, W. (2024). VehiGAN: Generative adversarial networks for adversarially robust V2X misbehavior detection systems. In Proceedings of the 44th IEEE International Conference on Distributed Computing Systems (ICDCS).
