---
layout: publication
type: publication
title: "Forecasting the Ionosphere from Sparse GNSS Data with Temporal-Fusion Transformers"
# All dates must be YYYY-MM-DD format!
date: 2025-12-06
published: true
labels:
---

## Abstract

The ionosphere critically influences Global Navigation Satellite Systems (GNSS), satellite communications, and Low Earth Orbit (LEO) operations, yet accurate prediction of its variability remains challenging due to nonlinear couplings between solar, geomagnetic, and thermospheric drivers. Total Electron Content (TEC), a key ionospheric parameter, is derived from GNSS observations, but its reliable forecasting is limited by the sparse nature of global measurements and the limited accuracy of empirical models, especially during strong space weather conditions. In this work, we present a machine learning framework for ionospheric TEC forecasting that leverages Temporal Fusion Transformers (TFT) to predict sparse ionosphere data. Our approach accommodates heterogeneous input sources, including solar irradiance, geomagnetic indices, and GNSS-derived vertical TEC, and applies preprocessing and temporal alignment strategies. Experiments spanning 2010-2025 demonstrate that the model achieves robust predictions up to 24 hours ahead, with root mean square errors as low as 3.33 TECU. Results highlight that solar EUV irradiance provides the strongest predictive signals. Beyond forecasting accuracy, the framework offers interpretability through attention-based analysis, supporting both operational applications and scientific discovery. To encourage reproducibility and community-driven development, we release the full implementation as the open-source toolkit \texttt{ionopy}.

### Authors

Giacomo Acciarini, Simone Mestici, Halil Kelebek, Linnea Wolniewicz, Michael Vergalla, Madhulika Guhathakurta, Olga Verkhoglyadova, Thomas Berger, Bala Poduval, Atılım Güneş Baydin, Frank Soboczenski

[Read the full paper on the ML4PhysicalSciences workshop page](https://ml4physicalsciences.github.io/2025/files/NeurIPS_ML4PS_2025_327.pdf)