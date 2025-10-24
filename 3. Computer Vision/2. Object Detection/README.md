# 🎯 Object Detection

> Moving beyond classification to **localizing and identifying multiple objects** within an image.

---

## 🧩 Concepts

Object Detection extends image classification by predicting *where* objects appear and *what* they are.  
It combines classification and regression in one framework.

Core topics:
- Sliding windows and region proposals  
- Anchor boxes and bounding boxes   
- Two-stage detectors (R-CNN, Faster R-CNN)  
- One-stage detectors (YOLO, SSD)  
- Data annotation and augmentation  

## ⚙️ Implementation Plan

- [ ] Visualize bounding boxes and labels  
- [ ] Implement simple selective search proposal demo  
- [ ] Train or fine-tune Faster R-CNN (PyTorch)  
- [ ] Test YOLOv5 or SSD pretrained models  
- [ ] Measure IoU and mAP  
- [ ] Visualize detection outputs  

---

## 📊 Evaluation Metrics

- mAP (mean Average Precision)  
- IoU (Intersection over Union)  
- Precision–Recall Curve  
- FPS (Frames per Second)  

---

## 🧪 Experiments & Insights

- Compare one-stage vs two-stage detectors  
- Analyze detection confidence thresholds  
- Observe false positives and occlusions  
- Benchmark inference speed vs accuracy trade-offs  

---

## 📚 Resources

- *You Only Look Once* (Redmon et al., 2016)  
- *Faster R-CNN* (Ren et al., 2015)  
- *SSD: Single Shot MultiBox Detector* (Liu et al., 2016)  
- PyTorch Vision Models  
- Roboflow / COCO Dataset Docs  

---

## ✅ Progress

- [ ] Bounding box pipeline built  
- [ ] Faster R-CNN trained  
- [ ] YOLO tested  
- [ ] Metrics computed  
- [ ] Insights summarized  
