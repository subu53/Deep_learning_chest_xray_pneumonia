# 🩻 Pneumonia Detection from Chest X-Rays  
Python | Deep Learning | Medical Imaging | Transfer Learning  

---

## 🔍 Project Overview
Pneumonia is a serious lung infection that requires early and accurate diagnosis.  
This project leverages **deep learning with transfer learning (ResNet)** to classify chest X-ray images as **Pneumonia** or **Normal**.  

The dataset used is the **Chest X-ray Pneumonia Dataset (Kaggle)**, containing over 5,000 labeled images.  

---

## ⚙️ Tech Stack & Tools
- **Languages:** Python 🐍  
- **Libraries:** FastAI, PyTorch, Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn, Pillow  
- **Techniques:** Transfer Learning, CNNs, EDA, Data Augmentation  
- **Deliverables:** Jupyter Notebook with analysis + performance evaluation  

---

## 📈 Key Results
✅ Best Model: **ResNet34 (transfer learning)**  
🎯 Accuracy: **>90%** on test set  
📊 Precision/Recall balance: High sensitivity for Pneumonia detection  
⏱️ Training Efficiency: Transfer learning reduced training time significantly  

The model demonstrated strong diagnostic performance, making it a promising candidate for medical imaging applications.  

---

## 💡 Insights & Discussion
**Model Performance**  
- Transfer learning allowed high accuracy with fewer training epochs.  
- ResNet34 balanced performance and efficiency better than deeper networks.  

**Potential Applications**  
- Clinical decision support system to assist radiologists.  
- Screening tool in low-resource settings where medical staff are limited.  

**Next Steps**  
- Extend to larger, multi-hospital datasets for better generalization.  
- Add interpretability (Grad-CAM/SHAP) to visualize decision-making.  
- Deploy as a simple demo app for accessibility.  

---

## 🚀 How to Run
Clone this repo:
```bash

## 🚀 How to Run

**1. Clone this repo**
```bash
git clone https://github.com/your-username/pneumonia-detection.git
cd pneumonia-detection

git clone https://github.com/your-username/pneumonia-detection.git
cd pneumonia-detection
2. Install requirements

pip install -r requirements.txt


3. Download dataset from Kaggle

kaggle datasets download -d paultimothymooney/chest-xray-pneumonia -p ./data --unzip


4. Run the notebook

jupyter notebook chest_xray_pneumonia.ipynb


Or open directly in Google Colab and enable GPU ⚡.

🎯 Why This Project Matters

This project demonstrates end-to-end machine learning workflow in a real-world healthcare context:

Problem framing in the medical domain 🩺

Data preparation & exploratory analysis 📊

Deep learning with transfer learning 🤖

Model evaluation & interpretation 🔍

Discussion of real-world impact 💡

👉 A strong example of applying AI to solve impactful problems in healthcare.

👨‍💻 Author

Sammy S Mutuku
Aspiring Data Scientist & Machine Learning Enthusiast

🔗 LinkedIn
 | 📂 Portfolio

⚡ If you found this project interesting, consider giving it a ⭐ on GitHub!
