---
layout: project
type: project
image: img/anomaly_detection/anomaly_detection.png
title: "Dipper Detector"
date: 2025
published: true
labels:
summary: "Probabilistic detection of anomalous dimming in stellar light curves"
---

The goal of this project is to detect anomalies in stellar lightcurves, specifically 'dipper' events which are common in young stars. We are currently working with data from the Kepler K2 mission and modeling the lightcurve with a Gaussian process, so that we can compare the model prediction with true data to assess the likelihood of an interval being anomalous. Because the full probabilistic model is computationally prohibitive, we propose two efficient algorithms to reduce the cost of detecting anomalies that occur at short timescales relative to the “normal” variability of the light curve. 

I presented this work at the Center for Decoding the Universe Annual Conference in June, 2025.

[Watch my talk at the Center for Decoding the Universe Annual Conference](https://www.youtube.com/watch?v=4NGTrpEGFmA&list=PLhVh5i3WeQh78S8zJa1_BrZPBsb45IHQg&index=5)
[See the project on GitHub](https://github.com/linneawolniewicz/dipper-detection)