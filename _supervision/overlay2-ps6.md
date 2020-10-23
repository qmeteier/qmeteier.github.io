---
title: "Communication between a mobile application and a driving simulator for automated driving"
collection: supervision
type: "Semester project"
permalink: /supervision/overlay-ps6
venue: "HES-SO // University of Applied Sciences Western Switzerland"
date: 2019-06-30
location: "Fribourg, Switzerland"
---

* 1 student to supervise.
* The student worked 4 hours a week for 3 months.
* Approximately 1 meeting per month.


Context of the project 
======

To date, technological advances have made it possible to automate vehicles. For example, a level 2 automated car offers partial autonomy, i.e. the system can manage the acceleration, deceleration and steering of a vehicle thanks to the information perceived by various vehicle sensors. However, vehicle automation still causes road accidents during testing. This is why the HumanTech Institute, in collaboration with He-Arc and the University of Freiburg, has launched the "Ad Vitam" project to explore new concepts of Human-Vehicle interaction to maintain driver's situation awareness and make future driving safer. The goal of this semester project is to implement the communication between a driving simulator and a mobile application developed in another project (Overlay). The main challenge was to start from the exisiting code of the driving simulator, coded in C#.


Tasks done by the student
======

* Analysis of the existing architecture
	* Proposition of a new architecture including the tablet with the mobile application
	* Choice of data structure model : Frames in JSON
	* Choice of technology to send information : IP with WebSocket
* Implementation of communication on the simulator and the mobile application
	* Implementing of the data structure chosen to send the information
	* Serialization/Deserialization of JSON frames
* Building a first prototype with a transparent layout
* Functional tests of the prototype
