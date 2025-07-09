---
title: "Endoscopic Surgical Instrument Autonomous Identification (Object detection)"
date: 2021-06-01
end_date: 2022-03-31
field: "Medical AI, Object Detection"
status: "Completed"
summary: "Arrow bounding box model for surgical instrument detection with enhanced real-time performance."
---

**Duration:** Jun 2021 - Mar 2022  
**Field:** Medical AI, Object Detection

### Main Contributions:
1. Aiming at the problem that the key information (length and angle) is missing in the traditional bounding box recognition method of medical surgery, the arrow bounding box model is proposed to consider the real-time and information expression.  
2. The Arrow OBB-YOLO network for predicting the arrow bounding box is constructed, and the arrow is constrained inside the bounding box by coordinate transformation.  
3. The model's prediction performance is enhanced by the optimal expression of the arrow error (the coordinate error, the length, and the angle error). The gradient explosion problem caused by multiple solutions of atan() is avoided by rewriting the angle error function. A step-by-step training optimization method for the arrow bounding box is proposed, which significantly speeds up the convergence speed of the model.
