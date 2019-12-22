+++
# Date this page was created.
date = 2018-09-07T00:00:00

# Project title.
title = "Heart Valve Biaxial Mechanical Testing"

# Project summary to display on homepage.
summary = "Characterizing the mechanics of heart valve leaflet tissue through biaxial mechanical testing."
# This page contains information about 
# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "projects/biax_testing_header.jpeg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["BBDL"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "projects/biax_testing.jpeg"
# caption = "Figures depicting the biaxial mechanical testing of porcine heart valve leaflet tissues."

+++

Four heart valves regulate blood flow through the heart. The mitral and tricuspid valves, or atrioventricular valves, are examined in this project. The mitral valve permits blood flow from the left atrium to the left ventricle but restricts blood flow in the opposite direction; The tricuspid valve serves the same function for blood flow between the right atrium and right ventricle. Degradation and disease can affect these valves, leading to impaired valve function and initializing blood backflow, or *regurgitation*. These diseases are often mechanically and structurally based, principally affecting the structure of the heart valve and the mechanical behavior of the valve tissue. Computational modeling has recently been used to better understand how disease-driven mechanical and structural alterations impair valve function. These models rely on accurate material data – i.e., data that describes how the tissue will deform when subjected to mechanical loading. A dearth of this material data exists for the mitral and tricuspid valves. As such, our project focused on obtaining and presenting material data for the leaflets of these heart valves.

To examine the valve tissue mechanics, we used biaxial testing methods. These methods apply loads in two tissue directions, and are essential for characterization of *anisotropic*, or directionally-dependent, tissue mechanics. Because of extensive fiber networks running through the tissue, heart valve leaflets exhibit significant mechanical anisotropy, and as such require testing by biaxial methods. We also used image-based deformation tracking techniques to improve the quality of data obtained and to avoid error from attachment effects (St. Venant effects). Our study captured the anisotropy and nonlinear mechanical response of each of the three leaflets of the tricuspid valve and the two leaflets of the mitral valve. We further examined how the biaxial testing parameters, such as loading rate, testing temperature, and animal donor (pig vs sheep vs lamb heart tissue), affected the observed mechanical response. To complement the mechanical responses observed in our testing, we carried out a brief structural analysis consisting of quantification of the distribution of chordae tendineae within the valves and a histological examination of the layered microstructure of the heart valves. We expect that the data obtained in our study will help researchers to model the healthy heart valves and to eventually provide a model-based tool for prediction of surgical outcomes.

Our group has also recently performed similar biaxial testing protocols to examine how the mechanical response of the tissue varies throughout the region of the leaflet. This study found significant differences in the mechanical response of the mitral and tricuspid valve leaflets in various regions, with central regions exhibiting a more characteristic anisotropic response and edge regions exhibiting a more isotropic mechanical response. This brief “regional” study has been submitted for publication and will hopefully be accepted for publication by early 2019.

Through this project, I gained extensive experience with material behavior modeling and tensor representations of deformation and tissue mechanics. Through utilizing image-based strain tracking in our samples, I learned about image tracking and digital image correlation techniques. In our processing of testing data, I performed software development and figure generation in **MATLAB**. I improved my leadership skills by managing the research team during the data collection, and by ensuring the procedures were uniformly implemented by each member. Finally, I gained valuable writing experience drafting our manuscript, "An investigation of the anisotropic mechanical properties and anatomical structure of porcine atrioventricular heart valves.” This manuscript and a talk concerning the content of the project are available below.
