---
layout: project
type: project
image: img/anomaly_detection/anomaly_detection.png
title: "Anomaly Detection for Stellar Light Curves"
date: 2024
published: true
labels:
summary: "Detecting anomalies in stellar light curves"
---

The goal of this project is to detect anomalies in stellar lightcurves, specifically 'dipper' events which are common in young stars. We are currently working with data from the Kepler K2 mission and modeling the lightcurve with a Gaussian process, so that we can compare the model prediction with true data to assess the likelihood of an interval being anomalous. We plan to compare the performance of an autoregressive model trained on many lightcurves in modeling the lightcurve and detecting anomalies against the Gaussian process baseline.

[See the project on GitHub](https://github.com/linneawolniewicz/dipper-detection)