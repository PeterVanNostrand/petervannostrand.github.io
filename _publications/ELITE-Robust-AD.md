---
title: "ELITE: Robust Deep Anomaly Detection with Meta Gradient"
collection: publications
permalink: /publication/ELITE-Robust-AD
excerpt: "Deep Learning techniques have been widely used in detecting anomalies from complex data. Most of these techniques are either unsupervised or semi-supervised because of a lack of a large number of labeled anomalies. However, they typically rely on a clean training data not polluted by anomalies to learn the distribution of the normal data. Otherwise, the learned distribution tends to be distorted and hence ineffective in distinguishing between normal and abnormal data. To solve this problem, we propose a novel approach called ELITE that uses a small number of labeled examples to infer the anomalies hidden in the training samples. It then turns these anomalies into useful signals that help to better detect anomalies from user data. Unlike the classical semi-supervised classification strategy which uses labeled examples as training data, ELITE uses them as validation set. It leverages the gradient of the validation loss to predict if one training sample is abnormal. The intuition is that correctly identifying the hidden anomalies could produce a better deep anomaly model with reduced validation loss. Our experiments on public benchmark datasets show that ELITE achieves up to 30% improvement in ROC AUC comparing to the state-of-the-art, yet robust to polluted training data."
date: 2021-08-14
venue: "Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery & Data Mining (KDD)"
slidesurl: "/files/ELITE/ELITE-KDD21-Slides.pptx"
paperurl: "/redirect/ELITE-PDF"
citation: "Huayi Zhang, Lei Cao, Peter VanNostrand, Samuel Madden, and Elke A. Rundensteiner. 2021. ELITE: Robust Deep Anomaly Detection with Meta Gradient. In Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery &amp; Data Mining (KDD '21). Association for Computing Machinery, New York, NY, USA, 2174–2182. https://doi.org/10.1145/3447548.3467320"
---

<link rel="stylesheet" type="text/css" media="all" href="/assets/css/widearticle.css" />

Deep Learning techniques have been widely used in detecting anomalies from complex data. Most of these techniques are either unsupervised or semi-supervised because of a lack of a large number of labeled anomalies. However, they typically rely on a clean training data not polluted by anomalies to learn the distribution of the normal data. Otherwise, the learned distribution tends to be distorted and hence ineffective in distinguishing between normal and abnormal data. To solve this problem, we propose a novel approach called ELITE that uses a small number of labeled examples to infer the anomalies hidden in the training samples. It then turns these anomalies into useful signals that help to better detect anomalies from user data. Unlike the classical semi-supervised classification strategy which uses labeled examples as training data, ELITE uses them as validation set. It leverages the gradient of the validation loss to predict if one training sample is abnormal. The intuition is that correctly identifying the hidden anomalies could produce a better deep anomaly model with reduced validation loss. Our experiments on public benchmark datasets show that ELITE achieves up to 30% improvement in ROC AUC comparing to the state-of-the-art, yet robust to polluted training data.

Downloads: [Paper](/redirect/ELITE-PDF) ⏐ [Code](https://github.com/Mazic4/ELITE) ⏐ [Slides](/files/ELITE/ELITE-KDD21-Slides.pptx)

### Presentation by Huayi Zhang at KDD 2021

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/E6JFPwq6N5s?si=wJzKvW0uzoKkZEyy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<br>
