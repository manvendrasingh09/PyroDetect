# <img src="https://github.com/manvendrasingh09/PyroDetect/blob/main/Resources/PyroDetect.png" alt="PyroDetect Logo" width="30" style="vertical-align: middle;"/> PyroDetect: Enhanced Wildfire Detection with Advanced Deep Learning

## Overview

This repository presents the research titled **"Enhanced Wildfire Detection with Advanced Deep Learning Algorithms"**, conducted at **Vellore Institute of Technology (VIT), India**.

The project, **PyroDetect**, introduces a novel AI-powered wildfire detection system leveraging **Convolutional Neural Networks (CNNs) and Ensemble Learning** to improve fire detection accuracy and reduce false alarms. The model achieves a **high accuracy rate** using a curated dataset of high-resolution aerial and ground images. This repository outlines the methodology, datasets, and results but does **not** share the source code.

---

## Authors

- **Manvendra Singh**  
  [LinkedIn](https://www.linkedin.com/in/manvendrasingh09/)
- **Kshitiz Bhargava**  
  [LinkedIn](https://in.linkedin.com/in/kshitiz-b)
- **Abeer Mathur**  
  [LinkedIn](https://in.linkedin.com/in/abeermathur)

> Affiliation: Department of Software Systems, School of Computer Science & Engineering, Vellore Institute of Technology, India.  
> Contact Emails: m.s.jaunpur@gmail.com, kshitizbhargava2626@gmail.com, abeermathur17@gmail.com

---

## Project Highlights

- **Problem Addressed:** The increasing frequency and intensity of wildfires demand faster, more accurate detection methods. Current techniques suffer from slow response times and high false positives.
- **Solution Provided:** PyroDetect introduces an advanced AI-driven detection model integrating:
  - **Custom CNN Architecture** - Tailored for wildfire image classification.
  - **Ensemble Learning** - Combining multiple CNNs for higher accuracy.
  - **Data Augmentation** - Enhancing model generalization with diverse fire conditions.
- **Key Achievement:** PyroDetect achieves **high precision and recall**, outperforming traditional fire detection methods.

---

## Website & Application

Access the **PyroDetect** application and website here: [PyroDetect](https://pyrodetect.site)  
From this website, users can explore the system and its wildfire detection features.

---

## Methodology

### Proposed Architecture
The **PyroDetect** model integrates:

1. **Custom Convolutional Neural Network (CNN):**
   - Designed for accurate wildfire detection using deep feature extraction.
   - Includes activation functions, batch normalization, and dropout layers for optimized learning.
2. **Ensemble Learning:**
   - Combines multiple CNN models for improved classification accuracy.
3. **Dataset Augmentation:**
   - Image resizing, brightness adjustments, and noise reduction to enhance robustness.

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
| Model | Accuracy | Precision | Recall |
|--------|----------|-----------|--------|
| Custom CNN | 95.6% | 94.2% | 96.1% |
| Ensemble Learning | 97.3% | 96.8% | 97.9% |

### Evaluation Metrics
- **Confusion Matrix:**
  - True Positives: **2631**
  - True Negatives: **2678**
  - False Positives: **42**
  - False Negatives: **49**
- **Performance Graphs:**
  - **ROC Curve:** AUC = **0.993**
  - **Precision-Recall Curve:** AUC = **0.990**

### Visuals

1. **Confusion Matrix**  
   ![Confusion Matrix](https://github.com/manvendrasingh09/PyroDetect/blob/main/Resources/Confusion%20Matrix.png)

2. **Training Accuracy**  
   ![Training Accuracy](https://github.com/MAKnova/PyroDetect/blob/main/Resources/Training%20Accuracy.png)

3. **Training Loss**  
   ![Training Loss](https://github.com/MAKnova/PyroDetect/blob/main/Resources/Training%20Loss.png)

4. **ROC Curve**  
   ![ROC Curve](https://github.com/manvendrasingh09/PyroDetect/blob/main/Resources/ROC.png)

5. **Precision-Recall Curve**  
   ![ROC Curve](https://github.com/manvendrasingh09/PyroDetect/blob/main/Resources/Recall.png)

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

---

## Citation

If you use this work in your research, please cite it as follows:

### APA
Singh, M., Bhargava, K., & Mathur, A. (2024). *Enhanced Wildfire Detection with Advanced Deep Learning Algorithms.*

### IEEE
M. Singh, K. Bhargava, and A. Mathur, "Enhanced Wildfire Detection with Advanced Deep Learning Algorithms," *VIT University Research*, 2024.

### BibTeX
```bibtex
@inproceedings{Singh2024,
  author    = {Singh, Manvendra and Bhargava, Kshitiz and Mathur, Abeer},
  title     = {Enhanced Wildfire Detection with Advanced Deep Learning Algorithms},
  booktitle = {VIT University Research},
  year      = {2024},
}
```

