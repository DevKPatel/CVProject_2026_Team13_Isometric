# CV_2026_13_Isometric

## Group member details:

| Member Name         | Email Id                                                  | Enrollment No |
| ------------------- | --------------------------------------------------------- | ------------- |
| Dev Patel    | [dev.p14@ahduni.edu.in](mailto:dev.p14@ahduni.edu.in)     | AU2544026     |
| Shreyas Patel         | [shreyas.p@ahduni.edu.in](mailto:shreyas.p@ahduni.edu.in)     | AU2544025     |
| Parth Thakkar | [parth.t2@ahduni.edu.in](mailto:parth.t2@ahduni.edu.in) | AU2544017     |
| Aakansha Jadhav      | [aakansha.j@ahduni.edu.in](mailto:aakansha.j@ahduni.edu.in)   | AU2544027     |

---

## 6. A Deep Learning Pipeline for Robust Wheat Counting in Multi-Object Field Scenes. 

### **About the Project**

This project addresses the "tedious manual measurement" of wheat phenotyping by automating wheat head localization using Deep Learning. Accurate wheat head 
localization is critical for crop yield estimation but is hindered by "overlapping plants," "wind blur," and "variable appearance" across global regions. Standard detection 
fails when wheat heads are densely packed or when environmental conditions (like lighting) change. This project aims to design a Deep Learning pipeline that 
generalizes across domains (different countries/continents) to identify and localize wheat heads in high-resolution imagery.

---

### **Milestones / Deliverables**

* Deep Learning Architecture Selection: Implement and compare state-of-the-art architectures such as YOLOv8, Faster R-CNN, or DETR (Detection Transformer) 
to handle dense object clusters.
* Performance Metrics: Evaluate the model using Average Precision (AP@50) and Average Domain Accuracy (ADA) to measure consistency across different geographic datasets.
* Localization Refinement: Tackle the "overlapping" problem by implementing Non-Maximum Suppression (NMS) or Soft-NMS to distinguish between individual 
wheat heads in clusters.
* End-to-end Framework: Deliver a Python-based inference tool that takes a field image as input and outputs a precise wheat head count and localization map

---

### **Dataset**

* https://www.aicrowd.com/challenges/global-wheat-challenge-2021
