# 🎥 Video Frame Extraction & Object Segmentation Pipeline
### Real-Time Object Analysis using YOLOv8

AI pipeline that extracts frames from video and performs object detection using YOLOv8 to convert raw video into structured visual insights.

---

## 🚀 What It Does

- Extracts frames from input video using OpenCV  
- Runs YOLOv8 object detection on each frame  
- Aggregates unique objects across the video  
- Filters noise (e.g., removing irrelevant detections like "person")  
- Generates external search links for detected objects  

---

## 🧠 Tech Stack

- Python  
- OpenCV  
- YOLOv8 (Ultralytics)

---

## 🔄 Pipeline

Video → Frame Extraction → YOLOv8 Detection → Object Aggregation → Filtering → Search Links

---

## 📦 Output Example

Detected objects:
airplane, bottle, cell phone, toothbrush, refrigerator, remote

Generated links:
- Amazon / Flipkart / eBay / Walmart search URLs per object

---

## 📌 Key Highlights

- Real-time video understanding  
- Frame-level object detection  
- Cross-frame aggregation of objects  
- Converts visual data into actionable insights  

```bash
pip install ultralytics opencv-python
