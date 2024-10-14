---
layout: publication
type: publication
title: "WV-Net: A foundation model for SAR WV-mode satellite imagery trained using contrastive self-supervised learning on 10 million images"
# All dates must be YYYY-MM-DD format!
date: 2024-06-24
published: true
labels:
---

## Authors

Yannik Glaser, Justin E. Stopa, Linnea M. Wolniewicz, Ralph Foster, Doug Vandemark, Alexis Mouche, Bertrand Chapron, Peter Sadowski

## Abstract

The European Space Agency's Copernicus Sentinel-1 (S-1) mission is a constellation of C-band synthetic aperture radar (SAR) satellites that provide unprecedented monitoring of the world's oceans. S-1's wave mode (WV) captures 20x20 km image patches at 5 m pixel resolution and is unaffected by cloud cover or time-of-day. The mission's open data policy has made SAR data easily accessible for a range of applications, but the need for manual image annotations is a bottleneck that hinders the use of machine learning methods. This study uses nearly 10 million WV-mode images and contrastive self-supervised learning to train a semantic embedding model called WV-Net. In multiple downstream tasks, WV-Net outperforms a comparable model that was pre-trained on natural images (ImageNet) with supervised learning. Experiments show improvements for estimating wave height (0.50 vs 0.60 RMSE using linear probing), estimating near-surface air temperature (0.90 vs 0.97 RMSE), and performing multilabel-classification of geophysical and atmospheric phenomena (0.96 vs 0.95 micro-averaged AUROC). WV-Net embeddings are also superior in an unsupervised image-retrieval task and scale better in data-sparse settings. Together, these results demonstrate that WV-Net embeddings can support geophysical research by providing a convenient foundation model for a variety of data analysis and exploration tasks.

## Full Paper
[Read the full paper on arXiv](https://arxiv.org/abs/2406.18765)