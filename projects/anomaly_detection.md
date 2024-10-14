---
layout: project
type: project
image: img/anomaly_detection/anomaly_detection.png
title: "Anomaly Detection for Stellar Light Curves"
date: 2024-10
published: true
labels:
  - Timeseries
  - Gaussian Processes
summary: "Detect anomalies in stellar light curves"
---

<img class="img-fluid" src="../img/anomaly_detection/supernova.jpg">

The goal of this project is to detect anomalies in stellar lightcurves, specifically 'dipper' events which are common in young stars. We are modeling the lightcurve with a Gaussian process and assessing the likelihood of points to determine whether they are anomalous. We are developing an autoregressive model of the lightcurves to compare to the performance of the Gaussian process.

Source: <a href="https://github.com/linneawolniewicz/dipper-detection"><i class="large github icon "></i>linneawolniewicz/dipper-detection</a>
