<h1 align="center">🫁 Pneumonia Detection using Deep Learning</h1>

<p align="center">
  <i>Detect Pneumonia from Chest X-rays using AI 🚀</i>
</p>

<p align="center">
  <b>AI-powered web app to detect Pneumonia using Deep Learning</b><br>
  Built with ❤️ by <b>Rehan Vora</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/DeepLearning-ResNet18-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Accuracy-95%25-brightgreen?style=for-the-badge">
  <img src="https://img.shields.io/badge/Framework-Streamlit-red?style=for-the-badge">
</p>

---

## 🎯 Project Overview

✨ This is an **AI-powered medical imaging web application** that detects **Pneumonia** from chest X-ray images using a fine-tuned **ResNet18 model**.

💡 It demonstrates a complete **Machine Learning pipeline**:

* 📂 Data Loading
* 🧠 Model Training
* 📊 Evaluation
* 🌐 Deployment (Streamlit)

---

## 🖥️ App Preview

<p align="center">
  <img src="https://raw.githubusercontent.com/Abhhiiissshhek/pneumonia-detection/main/screenshot.png" width="800"/>
</p>

---

## 🚀 Features

* 📤 Upload chest X-ray images
* 🤖 Predicts **Normal / Pneumonia**
* ⚡ Real-time inference
* 🎨 Clean & interactive UI using Streamlit

---

## 🧠 Model Architecture

| Component        | Description                       |
| ---------------- | --------------------------------- |
| 🧠 Model         | ResNet18 (Pretrained on ImageNet) |
| 🔁 Technique     | Transfer Learning                 |
| 🎯 Classes       | Binary (Normal / Pneumonia)       |
| 📉 Loss Function | CrossEntropyLoss                  |
| ⚙️ Optimizer     | Adam                              |

---

## 📊 Performance Metrics

| Metric              | Value |
| ------------------- | ----- |
| ✅ Accuracy          | ~95%  |
| 🔍 Pneumonia Recall | ~96%  |
| ❗ False Negatives   | 32    |

> ⚠️ In medical AI, minimizing false negatives is critical.
> This model achieves ~96% recall, reducing missed diagnoses.

---

## ⚙️ Installation & Setup

```bash
git clone https://github.com/rehanvhora778/pneumonia-detection.git
cd pneumonia-detection
pip install -r requirements.txt
streamlit run app.py
```

✔️ Open browser → Upload image → Get prediction

---

## 📁 Project Structure

```
pneumonia-detection/
│
├── app.py
├── src/
├── requirements.txt
├── README.md
```

---

## 📂 Dataset

📌 Chest X-ray dataset from Kaggle
(Not included due to large size)

---

## ⚠️ Note

* `.pth` model file is not included
* Train the model using `train.py`

---

## 🌐 Live Demo

🚧 Coming Soon...

---

## 🚀 Future Enhancements

* 🔻 Reduce false negatives
* 📈 Add confidence score
* ☁️ Deploy online (Render / AWS / HuggingFace)
* 🧠 Improve generalization

---

## 🧠 Key Learnings

✔️ Built end-to-end ML pipeline
✔️ Learned Transfer Learning using ResNet18
✔️ Understood importance of Recall in medical AI
✔️ Deployed model using Streamlit

---

## 👨‍💻 Author

<p align="center">
  <b>Rehan Vora</b><br>
  🚀 AI & Full Stack Developer<br><br>
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
