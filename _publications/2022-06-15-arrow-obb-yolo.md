---
title: "Autonomous Recognition of Multiple Surgical Instruments Tips Based on Arrow OBB-YOLO Network"
collection: publications
permalink: /publication/arrow-obb-yolo/
excerpt: "We propose an Arrow OBB-YOLO network to detect and recognize the tips of multiple surgical instruments in laparoscopic images."
date: 2022-06-15
venue: "IEEE Transactions on Instrumentation and Measurement"
paperurl: "https://ieeexplore.ieee.org/document/9743445"
citation: "Peng, J., **Chen, Q.**, Kang, L., Jie, H., & Han, Y. (2022). Autonomous recognition of multiple surgical instruments tips based on arrow OBB-YOLO network. *IEEE Transactions on Instrumentation and Measurement*, 71, 1–13."
excerpt_separator: "<!--more-->"
---

In this paper, we present an autonomous recognition of multiple surgical instrument tips based on arrow object bounding box (OBB)-YOLO network prediction, the proposed method not only realizes the recognition and localization of key parts of the instrument, but also uses arrows to enhance the expression of critical information such as the tip angle under the premise of meeting the real-time requirements for medical scenes.

<!--more-->

### Highlights
- A new representation model for surgical instrument recognition based on Arrow OBB. A more comprehensive expression of key information of surgical instruments is achieved, the corresponding arrow error optimization solving method is given, and an enhanced BB model with arrow constraints is implemented using coordinate transformation.
- An step-by-step training optimization method is used to accelerate the convergence rate of the model. This method divides the training process into two phases (i.e., BB optimization and arrow optimization), based on the Arrow OBB, and the corresponding tracking area is generated to provide an information guide for the adjustment of the FOV of the endoscope.
- A publicly available medical instrument identification dataset containing high-resolution images from a large variety of instrument and scene categories that researchers involved in device identification can use to validate ideas and networks.

[📄 Full Paper (IEEE Xplore)](https://ieeexplore.ieee.org/document/9743445)
