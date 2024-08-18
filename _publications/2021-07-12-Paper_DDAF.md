---
title: "DDAF: Deceptive Data Acquisition Framework against Stealthy Attacks in Cyber-Physical Systems"
collection: publications
permalink: /publication/2021-07-12-Paper_DDAF
excerpt: 'This paper proposed a deception defense-based data acquisition framework for any hierarchical CPSs network.'
date: 2021-07-12
venue: 'EEE 45th Annual Computers, Software, and Applications Conference (COMPSAC)'
# slidesurl: 'http://shahriar0651.github.io/files/slides2.pdf'
paperurl: 'http://shahriar0651.github.io/files/paper_2021_DDAF.pdf'
citation: 'Shahriar, M. H., Rahman, M. A., Haque, N. I., & Chowdhury, B. (2021, July). DDAF: Deceptive Data Acquisition Framework against Stealthy Attacks in Cyber-Physical Systems. In 2021 IEEE 45th Annual Computers, Software, and Applications Conference (COMPSAC) (pp. 725-734). IEEE.'
---

Cyber-physical systems (CPSs) and the Internet of Things (IoT) are converging towards a hybrid platform that is becoming ubiquitous in all modern infrastructures. The massive deployment of CPS requires comprehensive, secure, and reliable communication. The integration of complex and heterogeneous systems makes enormous space for the adversaries to get into the network and inject malicious data. To obfuscate and mislead the attackers, we propose DDAF, a deception defense-based data acquisition framework for a hierarchical communication network of CPSs. Each switch in the hierarchical network generates a random pattern of addresses/IDs by shuffling the original sensor IDs reported through it. Later, while sending the measurement data from remotely located sensors to the central controller, the switches craft the network packets by replacing the sensors’ original IDs with pre-generated deceptive IDs. Due to the deception, any stealthy attack turns into a random data injection and ends up as an outlier during the bad data detection process. By analyzing the outlier data, DDAF detects and localizes the attack points and the targeted sensors. DDAF is generic and highly scalable to be implemented in any size of networked control systems. Experimental results on the standard IEEE 14, 57, and 300 bus power systems show that DDAF can detect, mitigate, and localize almost 100% of the stealthy cyber-attacks. To the best of our knowledge, this is the first framework that implements complete randomization in the data acquisition of a networked control system.