---
title: "Classifying drivers' situational awareness based on psychophysiological data"
collection: supervision
type: "Master thesis"
permalink: /supervision/classif-sa-tor
venue: "University of Neuchâtel"
date: 2020-07-15
location: "Neuchâtel, Switzerland"
---

* 1 student to supervise.
* The student worked full-time for 5 months.
* 1 meeting per week.


Context of the project 
======

To date, technological advances have made it possible to automate vehicles. For example, a level 2 automated car offers partial autonomy, i.e. the system can manage the acceleration, deceleration and steering of a vehicle thanks to the information perceived by various vehicle sensors. However, vehicle automation still causes road accidents during testing. This is why the HumanTech Institute, in collaboration with He-Arc and the University of Freiburg, has launched the "Ad Vitam" project to make future driving safer. One goal of the AdVitam project is to investigate how to build a model to evaluate the driver's state in real-time and be able to adapt the interaction level in the car. In this context, the goal of this master thesis is to investigate if it is possible to classify the driver situation awarenss based on physiological signals. The data were collected on a fixed-based driving simulator where participants had to drive in conditional automation for 20 minutes. They also had to react accordingly to 6 Takeover Requests (TORs). The labels of each TOR was used for the classification task (dangerous vs. nont dangerous obstacle and static vs. moving obstacle).


Tasks done by the student
======

* Review of previous studies that did classification tasks with physiological data in driving studies
* Generation of different datasets based on physiological signals : ECG, EDA and Respiration
	* Processing the signals
	* Testing different time-windows to compute physiological indicators
* Statistical Analysis and Feature Selection
* Implementation of Machine Learning Algorithms using the Scikit Learn framework in Python
* Running classification tasks with a Grid Search and K-Fold validation Approach
* Discussing the results obtained with the different time windows, labels and algorithms
