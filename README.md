# <img src="https://github.com/manvendrasingh09/PyroDetect/blob/main/Resources/PyroDetect.png" alt="PyroDetect Logo" width="30" style="vertical-align: middle;"/> PyroDetect: Wildfire Detection using Deep Learning


## 📌 Overview

PyroDetect is an advanced wildfire detection system that leverages deep learning techniques to improve early fire detection accuracy and reduce false positives. The system is designed to process high-resolution aerial and ground-based imagery and can be integrated into real-time monitoring systems.

This project is part of our research at **Vellore Institute of Technology** under the guidance of **Kathiravan S**.

## 🚀 Motivation

Wildfires are increasing in frequency and intensity due to climate change. Existing wildfire detection methods (satellite imagery, ground sensors) suffer from:

- **Delayed Detection** 🚨 - Slow response times due to low temporal resolution.
- **Limited Coverage** 🌍 - Manual observations and sensors miss remote locations.
- **High False Alarm Rates** ⚠️ - Existing AI models often mistake non-fire elements as fire.

## 🏆 Objectives

✅ Develop a **deep learning model** to detect wildfires with **high accuracy**\
✅ Utilize **multi-source image datasets** to improve robustness\
✅ Reduce **false positives** by using **ensemble learning techniques**\
✅ Optimize the model for **real-time monitoring and deployment**

---

## 📂 Dataset

The dataset consists of **2,700 high-resolution RGB images** from sources like:

- **Government Databases**
- **Flickr**
- **Unsplash**

### 🔍 Dataset Characteristics:

- 🌲 **Diverse environmental scenarios** (different forest types, weather conditions)
- 📏 **Image Resolution:**
  - **Avg:** 4057×3155 pixels
  - **Min:** 153×206 pixels | **Max:** 19699×8974 pixels
- 🏔️ **Geographical Variety**: Images captured across multiple locations.

---

## 🔬 Methodology

We built a custom **Convolutional Neural Network (CNN)** designed to enhance feature extraction and improve wildfire detection accuracy.

### 🏗️ Model Architecture:

- **5 Convolutional Layers**
- **4 Pooling Layers**
- **2 Dense Layers**
- **Activation Functions:** LeakyReLU
- **Optimization Techniques:** Batch Normalization & Dropout

### 🔑 Key Features:

✅ **Ensemble Learning** - Combining models (e.g., YOLOv5, EfficientNet) to reduce false positives.\
✅ **Data Augmentation** - Resizing, Normalization, and Synthetic Image Generation.\
✅ **Real-time Monitoring Potential** - Optimized model for integration with IoT & satellite systems.

---

## 🛠️ Implementation

### 📥 Prerequisites

Ensure you have the following dependencies installed:

```bash
pip install tensorflow keras numpy matplotlib opencv-python
```

### 🚀 Training the Model

Run the following command to start training:

```bash
python train.py
```

### 📊 Evaluating the Model

```bash
python evaluate.py
```

---

## 📈 Results & Performance

Our model achieved:

- 🔥 **Detection Accuracy:** **90-99%**
- 🎯 **Precision & Recall:** Improved wildfire detection rates
- ⚡ **Low False Alarm Rate:** Optimized CNN filters for robust classification

---

## 🏗️ Future Work

🔹 **Real-time deployment** via IoT & satellite integration\
🔹 **More training data** from drone & thermal cameras\
🔹 **Optimized mobile deployment** for emergency responders

---

## 📜 Contributors

- **Manvendra Singh**
  [LinkedIn](https://in.linkedin.com/in/manvendrasingh09) | [Github](https://github.com/manvendrasingh09) | [Website](https://manvendrasingh.dev/)
- **Kshitiz Bhargava**
  [LinkedIn](https://in.linkedin.com/in/kshitiz-bhargava) | [Github](https://github.com/Kshitiz-b) | [Website](https://kshitizbhargava.com/)
- **Abeer Mathur**
  [LinkedIn](https://www.linkedin.com/in/abeermathur/) | [Github](https://github.com/AbeerMathur) | [Website](http://abeermathur.in/)

---

## 📜 Citation

If you use PyroDetect in your research, please cite:

```
@article{pyrodetect2024,
  title={PyroDetect: Enhanced Wildfire Detection with Advanced Deep Learning Algorithms},
  author={Singh, Manvendra and Bhargava, Kshitiz and Mathur, Abeer},
  journal={Vellore Institute of Technology Research},
  year={2024}
}
```

---

## 🤝 Acknowledgments

Special thanks to **Vellore Institute of Technology** for supporting this research.

For questions, feel free to reach out to us! 🚀

