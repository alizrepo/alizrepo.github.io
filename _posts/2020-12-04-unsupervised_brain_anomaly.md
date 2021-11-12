---
title:  "Unsupervised Algorithm for Brain Anomalies Localization in Electromagnetic Imaging"
mathjax: false
layout: post
categories: media
---

![Block diagram](/assets/photos/unsupervised_brain_anomaly.jpg)


A brain anomaly localization algorithm in an unsupervised machine learning (ML) framework is presented for electromagnetic brain imaging. The method is based on expected value estimation and takes the advantage of the highly symmetrical human brain. The algorithm processes signals collected from pairs of antennas that are positioned symmetrically around the head, discretizes the imaging domain into pixels, and computes the statistical fields between the antennas on the left and right sides of the head. Then, it concatenates their intensities along the axis normal to the imaging domain to compute the expected value for every pixel. The computed expected values are merged into a matrix containing expected values for all pixels. Pixels with higher intensity show the likelihood of an anomaly being present at that location. The assumption on brain symmetry from the electromagnetic perspective was tested on healthy volunteers using a 14-element array system with a working frequency band of 0.5 - 2.0 GHz. The obtained average similarity is 92% and it confirms the validity of the assumption. The same system is used to test the algorithm on different scenarios in simulations and experiments using realistic 3D head phantoms designed based on MRIs of real patients. The imaging results demonstrate the capability of the proposed algorithm to localize bleeding and estimate its size with less than 10% error in less than a minute, which makes it suitable for real-time use in emergency stroke scenarios.

[Link to the paper](https://ieeexplore.ieee.org/document/9281116)
