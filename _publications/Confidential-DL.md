---
title: "Confidential Deep Learning: Executing Proprietary Models on Untrusted Devices"
collection: publications
permalink: /publication/Confidential-DL
excerpt: "Deep Learning techniques have been widely used in detecting anomalies from complex data. Most of these techniques are either unsupervised or semi-supervised because of a lack of a large number of labeled anomalies. However, they typically rely on a clean training data not polluted by anomalies to learn the distribution of the normal data. Otherwise, the learned distribution tends to be distorted and hence ineffective in distinguishing between normal and abnormal data. To solve this problem, we propose a novel approach called ELITE that uses a small number of labeled examples to infer the anomalies hidden in the training samples. It then turns these anomalies into useful signals that help to better detect anomalies from user data. Unlike the classical semi-supervised classification strategy which uses labeled examples as training data, ELITE uses them as validation set. It leverages the gradient of the validation loss to predict if one training sample is abnormal. The intuition is that correctly identifying the hidden anomalies could produce a better deep anomaly model with reduced validation loss. Our experiments on public benchmark datasets show that ELITE achieves up to 30% improvement in ROC AUC comparing to the state-of-the-art, yet robust to polluted training data."
date: 2019-09-28
venue: "ArXiv | Great Lakes Security Day"
slidesurl: "/files/Confidential-Deep-Learning/Confidential-Deep-Learning-Slides.pptx"
paperurl: "https://doi.org/10.48550/arXiv.1908.10730"
citation: "Peter M. VanNostrand, Ioannis Kyriazis, Michelle Cheng, Tian Guo, and Robert J. Walls. 2019. Confidential Deep Learning: Executing Proprietary Models on Untrusted Devices. arXiv:1908.10730. https://doi.org/10.48550/arXiv.1908.10730."
---


Deep Learning techniques have been widely used in detecting anomalies from complex data. Most of these techniques are either unsupervised or semi-supervised because of a lack of a large number of labeled anomalies. However, they typically rely on a clean training data not polluted by anomalies to learn the distribution of the normal data. Otherwise, the learned distribution tends to be distorted and hence ineffective in distinguishing between normal and abnormal data. To solve this problem, we propose a novel approach called ELITE that uses a small number of labeled examples to infer the anomalies hidden in the training samples. It then turns these anomalies into useful signals that help to better detect anomalies from user data. Unlike the classical semi-supervised classification strategy which uses labeled examples as training data, ELITE uses them as validation set. It leverages the gradient of the validation loss to predict if one training sample is abnormal. The intuition is that correctly identifying the hidden anomalies could produce a better deep anomaly model with reduced validation loss. Our experiments on public benchmark datasets show that ELITE achieves up to 30% improvement in ROC AUC comparing to the state-of-the-art, yet robust to polluted training data.

*This work is published on ArXiV and was presented at Great Lakes Security Day in September 2019*

Downloads: [Paper](https://doi.org/10.48550/arXiv.1908.10730) ⏐ [Slides](/files/Confidential-Deep-Learning/Confidential-Deep-Learning-Slides.pptx)
