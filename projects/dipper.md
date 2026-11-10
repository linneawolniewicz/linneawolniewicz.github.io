---
layout: project
type: project
image: img/anomaly_detection/anomaly_detection.png
title: "Nāhiku: Dipper Detection in Stellar Light Curves"
date: 2026
published: true
labels:
summary: "An open-source Python package for probabilistic modeling and anomaly detection in stellar light curves"
---

I develop probabilistic methods to detect short dimming events in stellar light curves, including dipper events and candidate exocomet signatures. The challenge is to distinguish these events from a star's normal variability and observational noise. My approach uses Gaussian processes to model stellar variability and searches for intervals that are anomalous relative to that model.

This research is now available through **[Nāhiku](https://github.com/linneawolniewicz/nahiku)**, my open-source Python package for light-curve modeling and anomaly detection. Nāhiku is the ʻŌlelo Hawaiʻi name for the Big Dipper constellation.

### The Nāhiku Package

Nāhiku brings the modeling and search workflow into a reusable package. It supports:

- **Light-curve data and simulations:** loading Kepler and TESS observations or custom CSV data, generating synthetic light curves, and injecting anomalies to evaluate detection methods.
- **Stellar-variability modeling:** Gaussian processes with GPU acceleration through GPyTorch, plus prewhitening with the Balmung algorithm to remove stellar pulsations.
- **Anomaly detection:** a fast, iterative greedy search and an exhaustive search across candidate windows, with tools to visualize the results.

The package is available on PyPI for Python 3.12 and later:

```bash
pip install nahiku
```

[Explore the source code on GitHub](https://github.com/linneawolniewicz/nahiku) · [View the package on PyPI](https://pypi.org/project/nahiku/) · [Read the documentation and examples](https://nahiku.readthedocs.io/)

### Research Background

The project began with dipper detection in Kepler K2 light curves. Because a full probabilistic search is computationally expensive, my research explores efficient searches for anomalies on timescales shorter than the star's normal variability.

I presented this work at the Center for Decoding the Universe Annual Conference in June 2025.

[Watch my talk at the Center for Decoding the Universe Annual Conference](https://www.youtube.com/watch?v=4NGTrpEGFmA&list=PLhVh5i3WeQh78S8zJa1_BrZPBsb45IHQg&index=5)
