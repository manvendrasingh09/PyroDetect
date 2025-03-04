# <img src="https://github.com/manvendrasingh09/PyroDetect/blob/main/Resources/PyroDetect.png" alt="PyroDetect Logo" width="30" style="vertical-align: middle;"/> PyroDetect: Enhanced Wildfire Detection with Advanced Deep Learning

## Overview

This repository presents the research titled **"Enhanced Wildfire Detection with Advanced Deep Learning Algorithms"**, conducted at **Vellore Institute of Technology (VIT), India**.

The project, **PyroDetect**, introduces a novel AI-powered wildfire detection system leveraging **Convolutional Neural Networks (CNNs) and Ensemble Learning** to improve fire detection accuracy and reduce false alarms. The model achieves a **high accuracy rate** using a curated dataset of high-resolution aerial and ground images. This repository outlines the methodology, datasets, and results but does **not** share the source code.

---

## Authors

- **Manvendra Singh** [LinkedIn](https://www.linkedin.com/in/manvendrasingh09/)
- **Kshitiz Bhargava** [LinkedIn](https://in.linkedin.com/in/kshitiz-b)
- **Abeer Mathur** [LinkedIn](https://in.linkedin.com/in/abeermathur)

> Affiliation: Department of Software Systems, School of Computer Science & Engineering, Vellore Institute of Technology, India.  
> Contact Emails: m.s.jaunpur@gmail.com, kshitizbhargava2626@gmail.com, abeermathur17@gmail.com

---

## Project Highlights

- **Problem Addressed:** The increasing occurrence and severity of wildfires demand a faster, more accurate, and scalable detection system. Existing satellite-based and sensor-dependent methods suffer from delayed detection, limited coverage, and high false positives, making them inadequate for real-time wildfire monitoring.
- **Solution Provided:** PyroDetect employs a deep learning-based detection approach utilizing:
  - **Custom CNN Architecture** - A convolutional neural network optimized for wildfire detection, with layers specifically designed to extract fire-related features effectively.
  - **Optimized Training Strategy** - Implementing Adam optimizer, batch normalization, and dropout layers to improve generalization and prevent overfitting.  
  - **Data Augmentation** - Utilizing image rescaling, normalization, and augmentation to enhance model performance across diverse wildfire conditions.
- **Key Achievement:** PyroDetect achieves high accuracy, precision, and recall, significantly improving upon traditional fire detection methods by reducing false alarms and enabling more reliable early warnings.

---

## Methodology

### Proposed Architecture
The **PyroDetect** model integrates:

1. **Custom Convolutional Neural Network (CNN):**
   - Designed for accurate wildfire detection using deep feature extraction.
   - Includes activation functions, batch normalization, and dropout layers for optimized learning.
   
2. **Dataset Augmentation:**
   - Image resizing, brightness adjustments, and noise reduction to enhance robustness.
   - Normalization and augmentation techniques to improve model generalization across diverse wildfire conditions.


### Dataset

**PyroDetect** utilizes a newly curated dataset of **2,700 high-resolution images**, sourced from:
- **Government wildfire databases**
- **Public repositories (Flickr, Unsplash)**
- **Aerial and ground-based images** covering diverse environmental conditions.

#### Dataset Statistics
| Metric | Value |
|--------|-------|
| Total Images | 2,700 |
| Average Resolution | 4057×3155 pixels |
| Min Resolution | 153×206 pixels |
| Max Resolution | 19699×8974 pixels |

---

## Results

### Model Performance
| Model       | Accuracy | Precision | Recall |
|------------|----------|-----------|--------|
| Custom CNN | 84.15%    | 87.80%    | 86.06% |

### Evaluation Metrics
- **Confusion Matrix:**
  - True Positives (TP): **216**
  - True Negatives (TN): **129**
  - False Positives (FP): **30**
  - False Negatives (FN): **35**
- **Performance Graphs:**
  - **ROC Curve:** AUC = **0.90**
  - **Precision-Recall Curve:** AUC = **0.99**


### Visuals

1. **Confusion Matrix**
   The confusion matrix highlights the high number of true positives and true negatives, demonstrating the model's reliability in wildfire detection.

   <img src="https://github.com/manvendrasingh09/PyroDetect/blob/main/Resources/Confusion%20Matrix.png" width="500"/>

3. **Training Accuracy**
   The PyroDetect model's training accuracy started at 50% and steadily increased, reaching 98% by the final epoch.

   <img src="https://github.com/manvendrasingh09/PyroDetect/blob/main/Resources/Training%20Accuracy.png" width="500"/>

5. **Training Loss**
   The PyroDetect model's training loss started at 1.6 and gradually decreased to 0.07, indicating effective learning during training. 

   <img src="https://github.com/manvendrasingh09/PyroDetect/blob/main/Resources/Training%20Loss.png" width="500"/>

7. **ROC Curve**
   The ROC curve, with an AUC of 0.993, underscores the model's ability to accurately distinguish between wildfire and non-wildfire images.

   <img src="https://github.com/manvendrasingh09/PyroDetect/blob/main/Resources/ROC.png" width="500"/>

9. **Precision-Recall Curve**
   The precision-recall curve, with an area of 0.99, showcases the model's strong capability to maintain high precision and recall across different thresholds.

   <img src="https://github.com/manvendrasingh09/PyroDetect/blob/main/Resources/Recall.png" width="500"/>


---

## How to Use

1. Visit [PyroDetect](https://pyrodetect.site) to access the application.
2. Upload an image of a suspected wildfire.
3. Receive a real-time classification result.

---

## Acknowledgments

We would like to extend our gratitude to:
- **VIT University** for their support.
- **Mentors and colleagues** for their valuable insights and guidance.

---

## License

This repository is for academic reference only.  
The source code for PyroDetect is proprietary and **not included** in this repository.
