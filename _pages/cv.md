---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B. Tech in Engineering Design and M. Tech Specialization in Biomedical Design, Indian Institute of Technology Madras, 2018
* M.S. in Computer Science, New Jersey Institute of Technology, 2020 (expected)
<!-- * Ph.D in Version Control Theory, GitHub University, 2018 (expected) -->

Research
======
* July 2017 - May 2018: Graduate Research Assistant
  * Indian Institute of Technology Madras
  * Thesis: Analysis of Fetal Cardiac Ultrasound Images using Deep Learning
    * Acquisition and Pre-processing of ultrasound images of Fetal Heart
    * Annotation of the images into different standard planes, like 4 Chamber, 3 Vessel, RVOT, LVOT and Arch View for detecting anomalies
    * Developing an automatic detection software using neural networks for deecting anomalies in Fetal Heart
    * Detecting Common anomalies like Congenital Heart diseases and septal defects sutomatically by analysing ultrasound data which helps save time for the Doctors
  * Supervisor: Dr. Ganapathy Krishnamurthy
  * Tools Used: Python, Tensorflow, matplotlib

Work experience
======
* July 2017 - May 2018: Graduate Teaching Assistant
  * Indian Institute of Technology Madras
  * Duties included: TA for the courses Analog and Digital Circuits and Machine Learning for Engineering and Science Applications
  * Supervisor: Dr. Ganapathy Krishnamurthy

* Dec 2016 - May 2017: Semester Intern
  * Predible Health
    * Automatic Segmentation of Liver CT Images using Deep Learning
    * Modified a deep learning model for automatic segmentation of Liver CT images
    * The developed model showed an increase in the accuracy of the UNET from 86.5% to 93.5%
    * Built a Deep Learning API to host the trained models on the AWS GPU instances for on-the-go image segmentation
    * Potential time saving of Radiologists’ task of segmentation from 3-4 hours to 25 minutes

* June 2016 - Aug 2016: Summer Intern
  * Airbus Group India
    * Developed a virtual cockpit for training pilots on Microsoft HoloLens
    * The data for training was received in almost real time with a time delay of not more than 200-300 ms from the Airbus headquarters in Toulouse, France
    * The application was built using the Unity Game Engine which takes data from Airbus headquarters in Toulouse for the simulation
    * Potential savings of USD 5000-6000 per trainee, because now the trainees would not need to go to headquarters for training on the physical system

* Dec 2015 - Jan 2016: Winter Intern
  * Titan Company Ltd.
    * Developed an Augmented Reality application for 3D try-on of eyewear in real time
    * Used Voila Jones algorithm for tracking 64 facial points for accurate placement of eyewear in real time
    * The Web application developed was written in ActionScript 3.0
    * The application was also ported to major mobile operating systems, i.e. Android and iOS
  
Skills
======
* Software Engineering
* Artificial Intelligence
  * Machine Learning
  * Deep Learning
* Object Oriented Programming Concepts
* Data Structures and Algorithms
* Networks and Security
  * Network Management
  * Cryptography
  * Internet and Higher Layer Protocols
* Programming Languages
  * C/C++, C#
  * Java
  * Python
  * MATLAB
  * HTML/CSS
  * Lua
  * SQL

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
