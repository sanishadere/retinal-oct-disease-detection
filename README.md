# 🧿 Retinal OCT Disease Detection Platform

A deep learning web app that analyzes Optical Coherence Tomography (OCT) retinal scans and classifies them into four categories: **CNV**, **DME**, **Drusen**, and **Normal** — helping streamline early detection of retinal diseases.

🔗 **Live App:** [sanisha-retinal-oct.streamlit.app](https://sanisha-retinal-oct.streamlit.app)

---

## 📌 About

Optical Coherence Tomography (OCT) is a widely used imaging technique in ophthalmology, with over 30 million scans performed annually. Manual analysis of these scans is time-consuming — this platform uses a trained deep learning model to automate classification, helping reduce diagnostic time and support clinical decision-making.

## ✨ Features

- 📤 Upload OCT scan images directly in the browser
- 🤖 Automated classification into 4 categories: CNV, DME, Drusen, Normal
- 📊 Instant prediction results with confidence
- 📖 Condition-specific information and recommendations
- 🎨 Clean, dark-themed responsive UI built with Streamlit

## 🧠 Model & Dataset

- **Architecture:** MobileNetV3 (transfer learning)
- **Dataset:** 84,495 labeled OCT images (train/val/test split)
- **Classes:** CNV, DME, Drusen, Normal
- Images sourced from multiple medical institutions, verified through a multi-tier expert grading process

## 🛠️ Tech Stack

- **Frontend/App:** Streamlit
- **ML Framework:** TensorFlow / Keras
- **Image Processing:** Pillow, NumPy
- **Deployment:** Streamlit Community Cloud

## 🚀 Running Locally

```bash
git clone https://github.com/sanishadere/retinal-oct-disease-detection.git
cd retinal-oct-disease-detection
pip install -r requirements.txt
streamlit run app.py
```

## 📬 Contact

- 📧 Email: sanishadere5@gmail.com
- 💼 LinkedIn: [Sanisha Dere](https://www.linkedin.com/in/sanisha-dere-8abb703b1)

---

*Built as part of academic/portfolio work exploring deep learning applications in medical imaging.*