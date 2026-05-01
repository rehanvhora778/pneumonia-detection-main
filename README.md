<h1 align="center">🫁 Pneumonia Detection using Deep Learning</h1>

<p align="center">
  <i>Detect Pneumonia from Chest X-rays using AI 🚀</i>
</p>

<p align="center">
  <b>👨‍💻 Developed by Rehan Vora</b><br>
  <a href="https://github.com/rehanvhora778">GitHub Profile</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/DeepLearning-ResNet18-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Accuracy-95%25-brightgreen?style=for-the-badge">
  <img src="https://img.shields.io/badge/Streamlit-WebApp-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">
</p>

---

## 🌟 Project Vision

This project is an **AI-powered medical diagnosis system** that analyzes **Chest X-ray images** to detect whether a patient is suffering from **Pneumonia or not**.

🔬 The goal is to demonstrate how **Deep Learning can assist doctors** by providing fast and reliable predictions.

---

## 🧠 How This Project Works (Complete Flow)

This project follows a full **end-to-end Machine Learning pipeline**:

```
Dataset → Preprocessing → Model Training → Evaluation → Deployment → Prediction
```

### 📌 Step-by-step Workflow:

1. 📂 **Dataset Collection**

   * Chest X-ray dataset downloaded from Kaggle

2. 🧹 **Data Preprocessing**

   * Image resizing
   * Normalization
   * Train/Test split

3. 🧠 **Model Training**

   * Using **ResNet18 (Transfer Learning)**
   * Replace final layer for binary classification

4. 📊 **Model Evaluation**

   * Accuracy, Recall calculated
   * Focus on minimizing **False Negatives**

5. 🌐 **Deployment**

   * Streamlit-based web interface

6. ⚡ **Prediction**

   * Upload X-ray → Model predicts result instantly

---

## 🖥️ Application Preview

<p align="center">
  <img src="https://raw.githubusercontent.com/Abhhiiissshhek/pneumonia-detection/main/screenshot.png" width="850"/>
</p>

---

## ✨ Key Features

🚀 What makes this project powerful:

* 📤 Upload real chest X-ray images
* 🤖 AI predicts **Normal / Pneumonia**
* ⚡ Instant results (real-time inference)
* 🎯 High recall for medical reliability
* 🎨 Clean and interactive UI

---

## 🧠 Model Architecture

| Feature       | Details               |
| ------------- | --------------------- |
| Model         | ResNet18              |
| Technique     | Transfer Learning     |
| Input         | Chest X-ray Images    |
| Output        | Binary Classification |
| Loss Function | CrossEntropyLoss      |
| Optimizer     | Adam                  |

---

## 📊 Performance Analysis

| Metric                | Value |
| --------------------- | ----- |
| ✅ Accuracy            | ~95%  |
| 🔍 Recall (Pneumonia) | ~96%  |
| ❗ False Negatives     | 32    |

> ⚠️ In healthcare AI, **False Negatives are dangerous**
> This model focuses on **detecting Pneumonia cases reliably**

---

## ⚙️ Complete Setup Guide (Step-by-Step)

Follow these steps carefully 👇

---

### 🔹 1. Clone the Repository

```bash
git clone https://github.com/rehanvhora778/pneumonia-detection.git
cd pneumonia-detection
```

---

### 🔹 2. Install Required Libraries

```bash
pip install -r requirements.txt
```

---

### 🔹 3. Prepare Dataset

* Download dataset from Kaggle
* Extract dataset
* Organize into:

```
dataset/
   ├── train/
   ├── test/
```

---

### 🔹 4. Train the Model

```bash
python train.py
```

✔️ This will:

* Train ResNet18 model
* Save model as `.pth` file

---

### 🔹 5. Run the Web Application

```bash
streamlit run app.py
```

✔️ Open browser → Upload image → Get prediction

---

## 📁 Project Structure

```
pneumonia-detection/
│
├── app.py                → Streamlit App
├── train.py              → Model Training Script
├── src/                  → Helper Modules
├── dataset/              → Training Data
├── requirements.txt
├── README.md
```

---

## 📂 Dataset

📌 Source: Kaggle Chest X-ray Dataset
(Not included due to size limitations)

---

## ⚠️ Important Notes

* Model file (`.pth`) not included
* Must train model before running app
* Ensure dataset is correctly structured

---

## 🚀 Future Enhancements

* 📉 Reduce false negatives further
* 📊 Add confidence score display
* 🌐 Deploy online (Render / HuggingFace)
* 🧠 Improve accuracy with larger dataset

---

## 🧠 Key Learnings

✔️ End-to-end ML pipeline development
✔️ Transfer Learning using ResNet18
✔️ Medical AI evaluation metrics
✔️ Streamlit deployment

---

## 👨‍💻 Author

<p align="center">
  <b>Rehan Vora</b><br>
  🚀 AI Developer<br><br>
  <a href="https://github.com/rehanvhora778">
    <img src="https://img.shields.io/badge/GitHub-rehanvhora778-black?style=for-the-badge&logo=github">
  </a>
</p>

---

## ⭐ Show Your Support

If you found this project useful:

👉 Give it a ⭐ on GitHub
👉 Share with others

---

<p align="center">
  💡 <i>"AI in healthcare can save lives — and this is a step towards it."</i>
</p>
