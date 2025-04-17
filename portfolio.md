---
title: ICS Ph.D. Portfolio
layout: home_no_footer
permalink: /portfolio/
---

# Ph.D. Portfolio
My portfolio items are contained on my personal website and below. Please scroll through the below page to find each of the portfolio contents.

## Statement of Purpose

I am a 3rd year Ph.D. student with a background in Astrophysics and a focus on machine learning (ML) for scientific discovery. I've been interested in machine learning since I took Andrew Ng's Coursera course with my siblings the summer before college, but did not begin doing research in ML until my Junior year of my undergrad. 

My first exposure to research was instead via an REU (Research Experience for Undergraduates) program hosted by the Institute for Astronomy at UH Mānoa (UHM) between the summer of my 2nd and 3rd year of undergrad. During this REU I did work that resulted in a first-author publication in the Astronomical Journal and a presentation at one of the largest Astronomy conferences: The American Astronomical Society's winter meeting in 2021. After this work, I got involved in a project applying k-means and an unsupervised convolutional neural network (CNN) to segment coronal holes in extreme ultra-violet images of the Sun, which we presented at the NeurIPS Machine Learning for the Physical Sciences (ML4PS) workshop in 2020. This project piqued my interest in ML, and the following summer before my 4th year I participated in a second REU hosted by MIT's Haystack Observatory, preparing a signal processing pipeline for seismic data from the Ross Ice Shelf in Antarctica to automatically detect ocean wave events. 

I came to UH to work with Dr. Peter Sadowski on ML for science, and since then have been involved in many projects, with a focus on astronomical applications and ML models that incorporate scientific domain knowledge as an inductive bias. My physics-informed projects have included exploratory work with Physics-informed neural networks, Evolutionary-informed neural networks, and Fourier Neural Operators. My Masters project used a neural network as a surrogate likelihood function to sample from the posterior distribution over parameters that describe the transport of Galactic Cosmic Rays in our heliosphere given flux observations with Hamiltonian Monte Carlo, a previously intractable problem. I have since presented this work at the ML4PS workshop at NeurIPS 2023, SUDS 2024, and SPAICE conference 2024, and am currently preparing it for publication in the Journal of Geophysical Research. I have also been a collaborator on two of my labmate Nick Glaser's projects, by fine-tuning models for regression tasks in his WV-Net paper (presented at AGU 2023) and training 3D CNNs as a part of an ongoing solar inversion project.

During my Masters, I also participated in a summer internship at Striveworks, a startup based in Austin, Texas. As a data science research and development intern, I researched traditional NLP models and LLMs performance (through fine-tuning and prompt engineering) on text classification tasks. This provided me with an opportunity to conduct ML research in an industrial setting, where model deployment and high-speed development cycles are prioritized.

My current research is focused on detecting anomalies in stellar time series data, specifically 'dipper' events which may correspond to exocomets and events of interest in the lightcurves of young stars. This work is in collaboration with Dr. Eric Gaidos, a professor in SOEST. Currently this work is conducted by measuring the reconstruction error of a Gaussian Process fit to the lightcurve, for which we have developed two algorithms that detect anomalies by removing and refitting low-likelihood intervals. The current challenge I am exploring in this work is replacing the Gaussian Process with a deep learning model that can retain an inductive bias for the periodic signals in the lightcurves. A deep learning model will generalize across the dataset and scale better to allow us to detect anomalies on a finer scale.

During my time at UHM, I have also been involved in outreach and community building activities, through my role as Outrech Coordinator (2023-2024) and Vice President (2024-2025) of Graduate Women in Science Hawaiʻi ([GWISH](https://www.gwishawaii.org/)), and by co-hosting the ICS graduate student space and coffee hour with Arianna Bunnell. Through GWISH I have built an outreach program from the ground up that delivers coding-first workshops to high school students around the state of Hawaiʻi. Under this outreach program, I have receieved two mini Cataylst Awards for Science Advancement grants and used the money to fund inter-island travel to bring our workshops to students on Molokaʻi, Lānaʻi, and the Big Island. Altogether, I have developed two Python coding workshops that are astronomy focused, trained 15 volunteers, and brought my workshops to 28 science classes at 8 high schools since November 2023. I have also brought students from Maryknoll High School for a tour of the UHM campus and labs 3 times. I am passionate about outreach and increasing the representation of women in science and building a community amongst graduate students in the ICS department, and look forward to expanding both of these initiatives during my Ph.D.

I’m driven by the rapid evolution of machine learning and its transformative potential for the physical sciences. As the field of astronomy is inundated with more data than ever before, the field is primed for breakthroughs—not just in applying ML to uncover new phenomena, but in developing models fundamentally shaped by scientific insight.As I continue my Ph.D., I look forward to pushing the boundaries of scientific discovery through deep learning. My career goals following my Ph.D. are to continue research in ML for scientific discvoery in industry, with my dream role being a researcher in the AI for science labs at Google or Microsoft. I’m excited to work at this intersection of ML and science, building tools that are not only powerful, but principled.

## Evidence of Core Competency
My M.Sc. was awarded by UH Mānoa in August 2024. It can be confirmed by navigating to the [UH Mānoa credential validation website](https://www.hawaii.edu/cecredentials/validate/) and typing in "24k7-8jyx-lvzz" as the CeDiD.

## Evidence of Scholarly Ability
### Publication(s)  in  reviewed  journals  or  conferences  that  are  relevant  to  the student’s professional interests
#### Publications
My publications are listed on my [publications page](https://linneawolniewicz.github.io/publications/). My contributions to those, and a few other relevant projects that are in preparation, are detailed below.

- Wolniewicz, L. M., Sadowski, P., Corti, C., 2024. “Neural Surrogate HMC: Accelerated Hamiltonian Monte Carlo with a Neural Network Surrogate
Likelihood” [Oral presentation]. AI in and for Space (SPAICE) Proceedings, 2024.
- - First-author work presented as an oral presentation at SPAICE in September, 2024. This work was also my Masters project. A preprint is available on [arXiv](https://arxiv.org/abs/2407.20432).

- Glaser, Y., Stopa, J. E., Wolniewicz, L. M., Foster, R., Vandemark, D., Mouche, A., Chapron, B., Sadowski, P., 2024. “WV-Net: A foundation model
for SAR WV-mode satellite imagery trained using contrastive self-supervised learning on 10 million images” [Oral presentation]. American Geophysical Union, 2023.
- - Collaborative work with my labmate, Yannik Glaser. I trained models for the supervised regression tasks, which included training regression heads on top of frozen embeddings and fine-tuning the entire model.

- Wolniewicz, L. M., Sadowski, P., Corti, C., 2023. “NeuralHMC: Accelerated Hamiltonian Monte Carlo with a Neural Network Surrogate Likeli-
hood”[Poster presentation]. Machine Learning for the Physical Sciences. Thirty-seventh Conference on Neural Information Processing Systems.
- - First author work presented as a poster presentation at ML4PS at NeurIPS. This work is an earlier version of my Masters project, which was presented at SPAICE (above).

- Wolniewicz, L. M., Berger, T., Huber, D., 2021. “The Stars Kepler Missed: Investigating the Kepler Target Selection Function Using Gaia DR2” The
Astronomical Journal, Volume 161, Number 5. 
- - First author paper published during my Bachelors.

- Tiwari, A. J., Hu, A., Tremblay, B., Smith, B., Wolniewicz, L. M., Penn, M., Kirk, M., Guidoni, S., Samanta, T., 2020. “SEARCH: SEgmentation of
polAR Coronal Holes”[Poster presentation]. Machine Learning for the Physical Sciences. Thirty-fourth Conference on Neural Information Processing
Systems.
- - Collaborative work conducted during my Bachelors. I conducted analysis with K-Means and worked on training the CNN at later tages of the project.

#### Conference presentations
For a full list of my presentations at relevant conferences, please refer to my [CV](https://linneawolniewicz.github.io/resources/linnea_wolniewicz_cv.pdf). 

### Other evidence of professional capacity
Additional information on my relevant work history, leadership, and outreach activities is included on my [CV](https://linneawolniewicz.github.io/resources/linnea_wolniewicz_cv.pdf). Some of these are also listed under my [projects](https://linneawolniewicz.github.io/#projects) and [outreach](https://linneawolniewicz.github.io/#outreach) sections on my homepage.

