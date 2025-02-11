# **YOLOv9-PlateDetection** 🚗🔍  
**Real-Time Vehicle License Plate Detection using YOLOv9**  

<div align="center">
  <img src="https://img.shields.io/badge/Python-3.9+-blue.svg" alt="Python version">  
  <img src="https://img.shields.io/badge/Deep%20Learning-YOLOv9-red.svg" alt="Deep Learning Model">
  <img src="https://img.shields.io/badge/Object%20Detection-✔-green.svg" alt="Object Detection">
  <img src="https://img.shields.io/badge/License-Apache%202.0-brightgreen.svg" alt="Apache License">
</div>  

---

## 🌟 **About the Project**  
**YOLOv9-PlateDetection** is an advanced vehicle **license plate detection system** built using **YOLOv9**. This deep learning-based approach enables accurate and real-time **license plate localization** in images and videos. The model is trained on a specialized dataset and optimized for high accuracy.  

### **Key Features**  
✅ **Real-time plate detection** with **YOLOv9**  
✅ **High accuracy**: **mAP@50 > 90%**, **mAP@50-95 > 70%**  
✅ **Dataset sourced from [PlateDetectionYolov8](https://universe.roboflow.com/object-detection-a8l1t/platedetectionyolov8/dataset/9)**  
✅ **Supports images & video streams** for detection  
✅ **Optimized with PyTorch, OpenCV, and Ultralytics**  

---

## 🔧 **Technologies & Tools**  
- **Deep Learning Model:** YOLOv9  
- **Programming Language:** Python (3.9+)  
- **Libraries & Frameworks:** PyTorch, OpenCV, Ultralytics  
- **Dataset:** [PlateDetectionYolov8](https://universe.roboflow.com/object-detection-a8l1t/platedetectionyolov8/dataset/9)  

---

## 📚 **Dataset Information**  
The dataset used for training is **PlateDetectionYolov8**, which consists of:  
- **8,876 labeled images** of vehicle license plates  
- **Preprocessed annotations** optimized for YOLO models  
- **Training, validation, and test splits**  

Download the dataset: [PlateDetectionYolov8](https://universe.roboflow.com/object-detection-a8l1t/platedetectionyolov8/dataset/9)  

---

## 🚀 **Getting Started**  

### **1️⃣ Installation**  
Clone the repository and install dependencies:  
```bash
git clone https://github.com/your-username/YOLOv9-PlateDetection.git
cd YOLOv9-PlateDetection
```
---

## 📸 Running Inference on an Image

If you're looking to run the model on an image and see the detection results, follow these steps:

### 1. Install Required Libraries
Make sure you have the necessary libraries installed:
```bash
pip install ultralytics torch opencv-python
```

### 2. Download the Pre-trained Weights
Use gdown to download the `best.pt` file:
```bash
!gdown 19gU4-AWEg4DdXvxY80sClcjyCABT0bg_
```

### 3. Run the Model on Your Image
Upload your test image to the files section (for example, if using Google Colab).
Update the image path in your script to point to your image file.

Here's an example usage snippet:

```python
# Example usage:
# Replace the image path with the path to your test image.
image_path = "/content/Plate-Sample.jpg"

# If you are training the model from the beginning, use this path.
# infer_and_visualize(image_path, model_path='/content/plate_detection/yolov9_plate_model/weights/best.pt')

# If you just load the best weights, use this path.
infer_and_visualize(image_path, model_path='/content/best.pt')
```
---

## 📊 **Performance Metrics**  
The model is evaluated on the test set using **Mean Average Precision (mAP)**:  

| Metric        | Score  |
|--------------|--------|
| **mAP@50**   | **90+%** |
| **mAP@50-95**| **70+%** |

---

## 🌟 **Future Improvements**  
- 🏎 **Faster inference time** optimization  
- 🎯 **Improving small plate detection** in low-quality images  
- 📈 **Dataset expansion** for broader generalization  
- 📹 **Integration with vehicle tracking** for real-world applications  

---

## 📜 **License**  
This project is licensed under the **Apache-2.0 License**. See the [LICENSE](LICENSE) file for details.  

---

## 🙏 **Acknowledgments**  
Special thanks to:  
- **[Roboflow](https://roboflow.com/)** for providing the **PlateDetectionYolov8 dataset**  
- **Ultralytics** for developing the **YOLO object detection framework**  

---

## 🤝 **Contributions**  
Contributions are welcome! If you’d like to improve this project, feel free to **fork the repository**, **create a pull request**, or **open an issue**.  

---

## 💬 **Contact**  
📧 - **Project Maintainer**: [M.Mardani](mailto:mortezammm80@gmail.com)

🌍 - **GitHub Profile**: [My GitHub Profile](https://github.com/morteza80mr)


🚀 **Let’s build intelligent vehicle recognition systems together!** 🚀  
