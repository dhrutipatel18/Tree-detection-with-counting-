# 🌳 Tree Detection, Counting & Spatial-Temporal Forest Change Monitoring

This project combines two complementary geospatial AI solutions: individual **tree detection and counting** from satellite imagery, and **temporal analysis** to monitor forest changes over time. Using state-of-the-art deep learning models and GIS tools, it aims to assist in ecological monitoring, vegetation management, and environmental planning.

---

## 📌 Project Overview

- **Tree Detection & Counting**: Detect and localize individual trees in high-resolution satellite imagery using YOLOv8 and Faster R-CNN.
- **Spatial-Temporal Change Detection**: Compare vegetation across multiple years to identify tree loss or growth using segmentation models like U-Net.

---

## 🎯 Objectives

- Automate detection and counting of trees using aerial/satellite images.
- Monitor forest cover changes over time due to deforestation or reforestation.
- Support decision-making with geospatial insights and reports.

---

## 🧰 Technologies & Tools

- **Languages**: Python  
- **Libraries**: PyTorch, TensorFlow, OpenCV, Pandas, NumPy  
- **Models**: YOLOv8, Faster R-CNN, U-Net  
- **Annotation**: Roboflow, LabelImg  
- **GIS Tools**: QGIS, Shapefiles  
- **Platforms**: Google Colab  

---

## 🔁 Workflow Overview

### Phase 1: Tree Detection and Counting
1. Collected high-resolution satellite images.
2. Annotated trees using LabelImg and Roboflow.
3. Trained YOLOv8 and Faster R-CNN for bounding box detection.
4. Evaluated models using mAP, IoU, and F1 Score.
5. Counted trees using Non-Max Suppression from YOLOv8 outputs.

### Phase 2: Spatial-Temporal Tree Change Analysis
1. Collected satellite imagery from multiple years for selected regions.
2. Applied segmentation models (U-Net) to extract vegetation masks.
3. Compared vegetation areas across years using pixel-based difference.
4. Visualized changes using QGIS (e.g., shapefiles, heatmaps).
5. Generated reports highlighting zones of deforestation or regrowth.

---

## 📊 Results Snapshot

| Model        | Task               | mAP@0.5 | F1 Score | Accuracy       |
|--------------|--------------------|---------|----------|----------------|
| YOLOv8       | Tree Detection      | 0.87    | 0.91     | ±95% count     |
| Faster R-CNN | Tree Detection      | 0.89    | 0.93     | ±97% count     |
| U-Net        | Segmentation (mask) | -       | 0.90     | Visual overlay |

---

## 📈 Key Insights

- YOLOv8 is efficient for real-time tree detection and scalable deployment.
- Faster R-CNN is more precise in dense vegetation scenarios.
- Spatial-temporal analysis helps track ecological changes and support land-use planning.
- Integration with QGIS bridges AI outputs with practical forest management workflows.

---

## 🗂️ Folder Structure


---

## 🔒 Code Access Notice

Due to the involvement of sensitive geographic data and internal datasets, the full source code is private.

📩 **For collaboration or code access, please contact the project owner.**

---

## 👤 Author

**Dhruti Patel**  
📧 dhrutiharhshadkumar@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/dhruti-p-)  
🐙 [GitHub](https://github.com/dhrutipatel18)

---

⭐ If you found this work useful or want to collaborate on geospatial AI, feel free to connect!
