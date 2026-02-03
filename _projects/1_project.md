---
layout: page
title: "EDGAR"
description: Autonomous driving in urban scenarios
img: assets/img/edgarteam.jpg
importance: 1
category: work
related_publications: false
---

<div style="position: relative; width: 100%; padding-bottom: 56.25%; height: 0; overflow: hidden;">
    <iframe src="https://www.youtube.com/embed/9ST2bMMGCHo?si=SQElL8sg9H5342uV" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

We were a team of PhD students with a clear goal: to navigate complex urban environments autonomously, comfortably, and safely. And we succeeded. During our final showcase, we drove over 20km through Munich—handling highways, country roads, and busy streets—with zero disengagements.

I led the data and detection modules. On the data side, I built the recording and preprocessing pipeline, handling everything from sensor calibration to data extraction.

To tackle a lack of labeling budget, I engineered a solution: I built an auto-labeling pipeline for point clouds based on the MS3D paper to generate pseudo-labels. I then implemented a training pipeline using CenterPoint, feeding it my pseudo-labels to train the model. This allowed us to accurately detect thousands of objects in real-time, ensuring a safe trajectory for the vehicle.

I am responsible for the detections you see in the right side.


Here is a description of actually what happens in the vehicle:

<div style="position: relative; width: 100%; padding-bottom: 56.25%; height: 0; overflow: hidden;">
    <iframe src="https://www.youtube.com/embed/xIIcQk6iMlY?si=O3HX1FXbsRdpBxps" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

<div style="position: relative; width: 100%; padding-bottom: 56.25%; height: 0; overflow: hidden;">
    <iframe src="https://www.youtube.com/embed/GwIIAQRNVas?si=zKax5oKhlUKxFgwR" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>