---
title: "Autonomous Recognition of Multiple Surgical Instruments Tips Based on Arrow OBB-YOLO Network"
collection: publications
category: journal
permalink: /publication/2022-06-20-arrow-obb-yolo
excerpt: "We propose an Arrow OBB-YOLO network for precise real-time recognition of surgical instrument tips. The method encodes both location and orientation using arrow-shaped bounding boxes."
date: 2022-06-20
venue: 'IEEE Transactions on Instrumentation and Measurement'
paperurl: 'https://ieeexplore.ieee.org/document/9743445'
citation: 'Peng, J., <b>Chen, Q.</b>, Kang, L., Jie, H., & Han, Y. (2022). "Autonomous recognition of multiple surgical instruments tips based on arrow OBB-YOLO network." <i>IEEE Transactions on Instrumentation and Measurement</i>, 71, 1–13.'
---

In this paper, we present a novel Arrow Object Bounding Box (OBB)-YOLO network for the autonomous recognition of multiple surgical instrument tips in laparoscopic scenes. The method not only detects and localizes surgical tools but also explicitly encodes critical directional information—such as tip orientation—through arrow annotations, all while meeting real-time processing requirements in clinical scenarios.

<!--more-->
### Highlights

- **Arrow OBB representation**: A new bounding box model that includes directional arrows, enabling enhanced interpretation of instrument tip angles. This is solved through coordinate transformation and arrow error optimization.
- **Two-phase training**: A stepwise optimization strategy that splits the training into BB detection and arrow refinement stages, accelerating convergence and improving stability.
- **Public dataset**: We publish a high-resolution dataset of surgical instruments across diverse categories and scenes, designed for benchmarking real-world tool recognition tasks in surgery.

[📄 Read full paper on IEEE Xplore](https://ieeexplore.ieee.org/document/9743445)
