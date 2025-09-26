# Pneumonia Detection from Chest X-Rays 🩻🤖

This project applies **deep learning with transfer learning** to detect **Pneumonia** in chest X-ray images.  
It demonstrates a clear end-to-end workflow: dataset preparation, exploratory data analysis, model training, and evaluation.

---

## 📌 Motivation
- Pneumonia is a serious lung infection where early detection is critical.
- Chest X-rays are a common diagnostic tool, and deep learning can provide fast, accurate support to radiologists.
- By leveraging **CNNs with transfer learning (ResNet)**, we can achieve state-of-the-art performance with minimal training time.

---

## 📂 Project Structure
pneumonia-detection/
│── chest_xray_pneumonia.ipynb # Clean and well-documented notebook
│── README.md
│── requirements.txt


---

## 🚀 Workflow
1. **Data Preparation**
   - Dataset: [Chest X-ray Pneumonia (Kaggle)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
   - Organized into `train/`, `val/`, `test/` folders.

2. **Exploratory Data Analysis (EDA)**
   - Visualized class distribution
   - Displayed random chest X-ray samples

3. **Model Training**
   - Transfer learning with **ResNet34/ResNet50** using [FastAI](https://docs.fast.ai/).
   - Applied data augmentation for stronger generalization.

4. **Evaluation**
   - Confusion matrix
   - Accuracy, Precision, Recall, and F1-score
   - Training/validation loss curves

5. **Next Steps**
   - Expand to larger and more diverse datasets
   - Apply Grad-CAM or SHAP for interpretability
   - Deploy as a simple web demo

---

## 📊 Results — Highlights
🔥 **Outstanding Accuracy**: Achieved **over 90% classification accuracy** on the test set.  
📈 **ResNet34** proved to be the sweet spot, combining efficiency with high performance.  
⏱️ **Fast training**: Transfer learning cut training time significantly compared to training from scratch.  
✅ Clear separation between **Pneumonia vs. Normal** cases demonstrated by confusion matrix and precision/recall scores.  

These results show that deep learning can be a **powerful ally in medical imaging tasks**.

---

## 💻 How to Run
### Option 1 — Google Colab
1. Open the notebook in Colab.
2. Enable GPU: *Runtime → Change runtime type → GPU*.
3. Upload your `kaggle.json` to download the dataset automatically.
4. Run cells in order.

### Option 2 — Local Setup
```bash
git clone https://github.com/yourusername/pneumonia-detection.git
cd pneumonia-detection
pip install -r requirements.txt
