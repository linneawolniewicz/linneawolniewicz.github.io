---
layout: publication
type: publication
title: "WV-Net: A Foundation Model for SAR Ocean Satellite Imagery"
# All dates must be YYYY-MM-DD format!
date: 2025-10-10
published: true
labels:
---

## Abstract

The European Space Agency’s Sentinel-1 (S-1) satellite mission has captured more than 10 million images of the ocean surface using C-band synthetic aperture radar (SAR WV mode). While machine learning is a promising approach for detecting and quantifying various geophysical signatures in these images, scientists are limited by the cost of manual data annotation for any particular task. We propose to use contrastive self-supervised learning on the full archive of unannotated WV-mode images to train a semantic embedding model named WV-Net. In experiments, we show that WV-Net embeddings outperform those from models that were pretrained with natural images (ImageNet) on four downstream tasks: multilabel classification [0.96 average area under the receiver operating characteristic (AUROC) vs 0.95], wave height regression [0.50 root-mean-square error (RMSE) vs 0.60], near-surface air temperature regression (0.90 RMSE vs 0.97), and unsupervised image retrieval [0.41 class-averaged mean average precision (mAP) vs 0.37]. WV-Net embeddings also scale better in data-sparse settings, and fine-tuned WV-Net models are more robust to hyperparameter choices. The WV-Net foundation model is publicly available and can be adapted to a variety of data analysis and exploration tasks in geophysical research.

### Authors

Yannik Glaser, Justin E. Stopa, Linnea M. Wolniewicz, Ralph Foster, Doug Vandemark, Alexis Mouche, Bertrand Chapron, Peter Sadowski

[Read the full paper at the AMS Journal](https://journals.ametsoc.org/view/journals/aies/4/4/AIES-D-25-0003.1.xml?tab_body=fulltext-display)