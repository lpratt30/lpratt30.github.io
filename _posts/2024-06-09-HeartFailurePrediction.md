---
layout: page
title: Predicting Heart Failure Using Deep Learning
gh-repo: lpratt30/lpratt30.github.io
---

We replicated the paper “Predicting Heart Failure Readmission from Clinical Notes Using Deep Learning”. Our
baseline Random Forest model outperformed their baseline RF model by .07 F1 score (0.67 to 0.74), contradicting
their conclusion and finding the paper to be incorrect. Did so by writing involved SQL query in Google Big Query to
extract data from MIMIC-III and using it to train a CNN on Word2Vec vectors and a Random Forest on TF-IDF.

A video presentation that summarizes our project and it's findings is viewable here: https://drive.google.com/file/d/1193f0dH4bQVdGwLypwOTTqYY1wHeZX2y/view?usp=sharing 

Our report is downloadable here: [Download the PDF](../assets/pdf/final_report.pdf)

Our code repository is publicly available here: [https://github.com/lpratt30/Risk ](https://github.com/lpratt30/PredictingHF) 



