# 🧿 Iris Recognition Pipeline using CASIA Iris-Thousand

This project presents a comprehensive pipeline for iris recognition using the **CASIA Iris-Thousand** dataset. It includes:

- ✅ Image preprocessing  
- ✅ Iris and pupil region annotation with **LabelMe**  
- ✅ SIFT-based feature extraction and keypoint detection

---

## 📁 Project Overview

The pipeline is divided into three main stages:

### 1. 🔄 Preprocessing
- Load raw images from the CASIA Iris-Thousand dataset.
- Extract and display iris images using annotations.
- Resize images to a standard shape (224x224).
- Save cleaned, standardized versions for analysis.

📍 **Input:** Raw CASIA images  
📍 **Output:** `/iris_images_preprocessed`

### 2. 📝 Annotation using LabelMe
- Annotate iris and pupil regions using **LabelMe** with circle shapes.
- Export annotations as `.json` files.
- Extract iris regions from annotated coordinates.

📍 **Input:** LabelMe `.json` files + original images  
📍 **Output:** Masked iris images (optionally visualized for confirmation)

### 3. 🔍 SIFT Feature Extraction
- Create a binary mask to exclude the pupil region.
- Apply **SIFT** on the remaining iris area.
- Visualize and save keypoints.

📍 **Input:** Preprocessed iris images  
📍 **Output:** Keypoint images and feature data

### Keypoints Data

Here are the keypoints detected for `S5026L07_eye_1_iris.png`:

## 📊 Conclusion
This pipeline efficiently processes iris images and extracts keypoints, enhancing the accuracy of iris recognition systems. Your insights and feedback will be invaluable for further improvements.

## 📄 Contact Information
Name: Raiane Yahiaoui
Email: ikba.king2015@gmail.com
LinkedIn: linkedin.com/in/yahiaoui-raiane-253911262

