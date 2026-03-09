---
title: "Cryptomining Traffic Detection via Statistical Filtering and Deep Learning"
collection: publications
category: conferences
permalink: /publication/2026-01-05-Cryptomining
excerpt: 'Cryptojacking, Encryption traffic, Deep learning, LSTM.'
date: 2026-01-05
venue: 'IFIP Working Group 11.9 on Digital Forensics'
paperurl: 'https://gswsfh.github.io/files/CRYPTOMINING_TRAFFIC.pdf'
---

As cryptojacking becomes increasingly prevalent, there is a growing need for eficient and accurate detection methods. However, since miningmalware typically communicates with mining pools via encrypted traffic.detection models trained on trafic metadata often struggle to recognizenew mining samples whose statistical characteristics difer from those of the training set. To address this issue, we propose Time-EmbeddingLSTM (TELSTM),an LSTM-based model that incorporates a noveltimestamp embedding as supplementary temporal information. Instead of processing time intervals sequentially, our method derives patterns directly from the embedded timestamps, enabling TELSTM to capture more stable mining behavior and generalize better to unseen miningtrafc. To ensure compatibility with high-speed networks, we also introduce an LSSVM-based classifer as a pre-processing stage. This flter efciently discards irrelevant traffic, reducing the computational load onthe subsequent deep-learning model and improving overall detection effciency, Experiments on a dataset containing simulated campus traffic and real-world mining trafic show that our approach achieves a false negative rate of 2.57% and a false positive rate of 0.10%, demonstrating its potential for practical deployment.


