# camouflage-object-detection using FusionYOLO

This project implements a **fusion-based object detection system** that uses both **RGB and thermal imaging** to detect **camouflaged people or objects** in natural environments such as forests.

It leverages the [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics) model for detecting human figures and simulates thermal imagery to improve detection performance in cases where camouflaged objects may be missed by RGB vision alone.

---

## Features

-  RGB and thermal-based detection fusion
-  Simulated thermal imagery from RGB input
-  Camouflage detection logic based on confidence comparison
-  Uses YOLOv8 for both RGB and thermal modalities
-  Fusion visualization with legends and annotations
   Outputs detection results with confidence scores

---

## Sample Output

The system outputs a side-by-side comparison of:

- RGB Detection
- Thermal Detection
- Fusion Detection

All with colored bounding boxes and a legend for:
- RGB-only detection (🔵)
- Thermal-only detection (🟡)
- Normal detection (🟢)
- Suspected camouflage (🟠)
- Confirmed camouflage (🔴)
  <img width="1547" height="1190" alt="image" src="https://github.com/user-attachments/assets/e6068977-f5c1-4dde-818d-e7bbb3151a54" />

---


