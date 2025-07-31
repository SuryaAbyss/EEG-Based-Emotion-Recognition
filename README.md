# EEG-Based Emotion Recognition 🎯🧠  
*A Comprehensive Comparison of Deep Learning (GRU) and Traditional Machine Learning Models for EEG Emotion Classification*

![EEG Signal Overview](electronics-12-02707-g001.png)

##
EEG Animation Preview
> EEG Signal Activity Visualized
![EEG Waves](https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExc2tiYnBhOGYwNjNvYnBxY3gxajcyNG5vM2V2a2xqbHl0OTV6OWhjbyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/l44QzsOLXxcrigdgI/giphy.gif)

## 🎬 Demo Animation

> EEG signal classification in action 🎥👇

![EEG Waves](https://media.giphy.com/media/SWoSkN6DxTszqIKEqv/giphy.gif)

---

## 📌 Overview

This project explores **EEG-based emotion recognition** using both **traditional machine learning models** and an advanced **Gated Recurrent Unit (GRU)** deep learning architecture. Emotions are classified into **Negative**, **Neutral**, and **Positive** using brainwave signals.

---

## 🧠 Use Case Areas

- 🧘‍♂️ Mental Health Monitoring  
- 🎮 Brain-Computer Interfaces (BCI)  
- 🤖 Emotion-Aware AI Systems  
- 🎓 Adaptive Learning Platforms  
- 🧑‍💻 Human-Computer Interaction

---

## 📂 Dataset

- 👥 **Trials:** 2132 EEG samples (4 seconds each)  
- 📊 **Features:** 2548 per sample (Time, Frequency, Time-Frequency, Spatial)
- 🎯 **Classes:** Negative (708), Neutral (716), Positive (708)

---

## 🧪 Techniques Used

### 🧱 Feature Domains:
- ⏱️ Time-based
- 🔊 Frequency (FFT)
- 🌊 Wavelets (Time-Frequency)
- 🧭 Spatial domain (Frontal Alpha Asymmetry)

### 🧠 ML & DL Models:
| Type | Models |
|------|--------|
| 💼 Traditional | Logistic Regression, SVM, KNN, Decision Tree, Naive Bayes |
| ⚡ Deep Learning | GRU-based RNN using TensorFlow/Keras |

---

## 📈 Results

| Model              | Accuracy | F1-Score | ROC AUC |
|-------------------|----------|----------|---------|
| 🥇 Logistic Regression | **96.09%** | 96.08% | 0.994 |
| 🌲 Decision Tree      | 95.31% | 95.32% | 0.974 |
| 💫 SVM                | 94.22% | 94.18% | 0.992 |
| 🧊 KNN                | 92.50% | 92.36% | 0.986 |
| 🧠 GRU (DL Model)     | 86.88% | 86.70% | 0.954 |
| 🧮 Naive Bayes        | 68.59% | 65.69% | 0.791 |

> 🔍 **Insight:** Feature-engineered datasets can outperform deep learning when designed well.

---

## 📊 Visual Dashboard

- 🎛️ Interactive Plotly Dashboard  
- 📈 ROC Curves & Confusion Matrices  
- 🧠 3D FFT Visualizations  
- 🔥 Feature Correlation Heatmaps

![Dashboard Animation](https://media.giphy.com/media/VbnUQpnihPSIgIXuZv/giphy.gif)

---

## 🔮 Future Scope

- ⚡ Real-time EEG Emotion Detection
- 🤖 Hybrid ML + DL for Edge Devices
- 💡 Feature Interpretability using SHAP/LIME
- 📲 Deployment in Mobile or Embedded Systems

---

## 🧑‍💻 Contributors

| 👨‍🎓 Name | 🎓 Roll No. | 🔧 Contribution |
|----------|------------|-----------------|
| **Surya Prakash Subudhiray** | 22053910 | Results, Dashboards, Visual Tools |
| **Smruti Ranjan Gansalvesh** | 22051284 | Feature Engineering, Preprocessing |
| **Soumya Bhunia** | 22051286 | Model Implementation & Tuning |

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&style=flat-square)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow&style=flat-square)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-yellow?logo=scikit-learn&style=flat-square)
![Plotly](https://img.shields.io/badge/Plotly-Visuals-9cf?logo=plotly&style=flat-square)
![Keras](https://img.shields.io/badge/Keras-DL-red?logo=keras&style=flat-square)

---

## 📚 References

- DEAP Dataset – Koelstra et al.
- Craik et al., *Deep Learning for EEG* (2019)
- Jenke et al., *Feature Selection for EEG Emotions* (IEEE)

---

## 📎 License

This project is open-source and available under the [MIT License](LICENSE).

---

> Designed with ❤️ by Team KIIT | 2025

