# 🧬 Automated Microscopic Blood Cell Analysis with MobileNetV2

This project implements a deep learning model using **MobileNetV2** for the automated analysis of microscopic blood cell images. It classifies cells like **RBCs (Red Blood Cells), WBCs (White Blood Cells), and Platelets**, and can assist in early disease detection from blood smears.

---

## 📌 Features

- ✅ Uses MobileNetV2 for efficient image classification
- 🩸 Identifies types of blood cells from microscope images
- 🧠 Transfer learning applied to real-world datasets
- 📊 Includes evaluation metrics like accuracy and confusion matrix

---

## 📁 Project Structure

📦 blood-cell-analysis/
├── 📂 blood_cell_data/ # Training & test images
        |--📂EOS 0001-1000
        |--📂LYT 0001-1000
        |--📂NGS 0001-1000
├── 📂 BloodCellProject/ # Jupyter notebooks for EDA & training
├── 📜 Project_code.py # Python script to train the model
├── 📜 predict.py # Predicts class from input image



---

## 📊 Model Details

- **Architecture**: MobileNetV2 (pretrained on ImageNet)
- **Additional Layers**:
  - GlobalAveragePooling2D
  - Dense(128, activation='relu')
  - Dense(num_classes, activation='softmax')

---

## 🧪 Dataset

- **BCCD Dataset** (Blood Cell and Detection): 
- Images labeled for RBC, WBC, Platelets

---




