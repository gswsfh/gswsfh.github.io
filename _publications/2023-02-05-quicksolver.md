---
title: "Quicksolver: A lightweight malicious domains detection system based on adaptive autoencoder"
collection: publications
category: conferences
permalink: /publication/2023-02-05-quicksolver
excerpt: 'malicious domains detection'
date: 2024-02-17
venue: 'Conference on Local Computer Networks (LCN)'
paperurl: 'https://gswsfh.github.io/files/Quicksolver_A_lightweight_malicious_domains_detection_system_based_on_adaptive_autoencoder.pdf'
citation: 'Wan, W., Wang, K., Wei, J., Gong, L., Huang, P., Fu, H., & Fu, Y. (2023, October). Quicksolver: A lightweight malicious domains detection system based on adaptive autoencoder. In 2023 IEEE 48th Conference on Local Computer Networks (LCN) (pp. 1-4). IEEE.'
---

The Domain Name System (DNS) plays a critical role in the Internet, making it a popular target for cyber attackers. Malicious actors use DNS to locate their command and control servers, and spam often contains URLs linked to domains that host malicious servers. Detecting such malicious domain activities is essential. While many prior works have shown promising results in detecting malicious domains, the time and storage required during detection are relatively high.In this paper, we propose a lightweight and effective malicious domain detection system called Quicksolver, ideal for large-scale networks. Our system uses only domain features, eliminating the need for additional costs associated with DNS traffic and registration information. Additionally, we use an improved autoencoder as our classifier, combining it with neural networks to avoid the need for setting and adjusting thresholds manually.We evaluated Quicksolver using malicious data collected from a certain ISP over three months. The results show that Quicksolver has better detection ability and lower detection time compared to other state-of-the-art methods. Furthermore, it can automatically identify unknown malicious domains that are misused in seven types of cyber attacks.
