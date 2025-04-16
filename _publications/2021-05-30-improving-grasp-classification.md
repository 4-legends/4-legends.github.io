---
title: "Improving Grasp Classification through Spatial Metrics Available from Sensors"
collection: publications
category: conference
permalink: /publication/2021-05-30-improving-grasp-classification
excerpt: "We present a method for classifying the quality of near-contact grasps using spatial metrics that are recoverable from sensor data. Current methods often rely on calculating precise contact points, which are difficult to calculate in real life, or on tactile sensors or image data, which may be unavailable for some applications."
date: 2021-05-30
venue: "2021 IEEE International Conference on Robotics and Automation (ICRA)"
paperurl: "https://ieeexplore.ieee.org/document/9561750"
pdfurl: "https://drive.google.com/file/d/1K-Qnzii96MN-2Vt9BSvwqXA0i3FGJM-e/view?usp=sharing"
citation: 'Nigel Swenson, Garrett Scott, Peter Bloch, Paresh Laxman Soni, Nuha Nishat, Anjali Harish Asar, Cindy Grimm, Xiaoli Fern, Ravi Balasubramanian, "Improving Grasp Classification through Spatial Metrics Available from Sensors", 2021 IEEE International Conference on Robotics and Automation (ICRA), 2021.'
---

We present a method for classifying the quality of near-contact grasps using spatial metrics that are recoverable from sensor data. Current methods often rely on calculating precise contact points, which are difficult to calculate in real life, or on tactile sensors or image data, which may be unavailable for some applications. Our method, in contrast, uses a mix of spatial metrics that do not depend on the fingers being in contact with the object, such as the object's approximate size and location. The grasp quality can be calculated before the fingers actually contact the object, enabling near-grasp quality prediction. Using a random forest classifier, the resulting system is able to predict grasp quality with 96% accuracy using spatial metrics based on the locations of the robot palm, fingers and object. Furthermore, it can maintain an accuracy of 90% when exposed to 10% noise across all its inputs.
