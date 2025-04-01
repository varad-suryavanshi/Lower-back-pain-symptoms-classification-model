# 🧠 Lower Back Pain Symptoms Classification Model

This project builds and evaluates a machine learning model to classify patients as either **normal** or **abnormal** based on biomechanical features of the spine. The goal is to assist in early detection of lower back pain using clinical data.

---

## 📌 Project Overview

Lower back pain is one of the most prevalent musculoskeletal conditions globally. Early detection and diagnosis can significantly improve treatment outcomes. This project applies supervised machine learning techniques to classify patient spine health using biomechanical data.

---

## 📊 Dataset

- **Source:** [UCI Vertebral Column Dataset](https://archive.ics.uci.edu/ml/datasets/Vertebral+Column)
- **Records:** 310 samples
- **Classes:**
  - `Normal`
  - `Abnormal` (Hernia or Spondylolisthesis)
- **Features:**
  - Pelvic incidence
  - Pelvic tilt
  - Lumbar lordosis angle
  - Sacral slope
  - Pelvic radius
  - Degree of spondylolisthesis

---

## 🧠 Models Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

Evaluation includes metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

---

## 📁 Project Structure

```text
lower-back-pain-classifier/
├── Lower Back pain symptoms classification model.ipynb   # Jupyter notebook with full workflow
├── requirements.txt                                      # Project dependencies
├── README.md                                             # Project overview
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/lower-back-pain-classifier.git
cd lower-back-pain-classifier
```

### 2. Create a virtual environment and install dependencies

```bash
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### 3. Run the notebook

Launch Jupyter Notebook or VS Code and open:

```bash
Lower Back pain symptoms classification model.ipynb
```

Explore EDA, train models, evaluate performance, and modify parameters as needed.

---

## 📄 License

This project is licensed under the **MIT License**.  
Dataset is provided by the UCI Machine Learning Repository for educational and research use.

---

Made with 💡 by [Varad Suryavanshi](https://github.com/varad-suryavanshi)  
Building smarter diagnostics through machine learning.
