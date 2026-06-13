#  SteelVision AI

An Explainable AI-powered Industrial Inspection System for Automated Steel Surface Defect Detection using ResNet18, Grad-CAM, and Streamlit.

---

##  Features

- Automated Steel Surface Defect Detection
- Explainable AI using Grad-CAM
- Confidence Score Analysis
- Defect Severity Assessment
- Corrective Action Recommendations
- PDF Inspection Report Generation
- Invalid Image Detection
- Interactive Streamlit Web Application

---

##  Application Screenshots

### Homepage

![Homepage](assets/Homepage.png)

---

### Prediction Dashboard

![Prediction](assets/Predictions.png)

---

### Grad-CAM Explainability

![GradCAM](assets/Gradcam.png)

---

### Inspection Report

![Report](assets/Report.png)

---

##  System Workflow

Image Upload

↓

Preprocessing

↓

ResNet18 Classification

↓

Confidence Analysis

↓

Grad-CAM Explainability

↓

Severity Assessment

↓

PDF Report Generation

---

##  Model Information

| Component | Details |
|------------|------------|
| Architecture | ResNet18 |
| Classes | 6 Defect Types |
| Framework | PyTorch |
| Explainability | Grad-CAM |
| Deployment | Streamlit |
| Language | Python |

---

##  Repository Structure

```text
assets/
notebooks/
presentation/
README.md
requirements.txt
```

---

##  Installation

```bash
git clone https://github.com/Venkatesh1410/SteelVision-AI.git

cd SteelVision-AI

pip install -r requirements.txt

streamlit run app.py
```

---

##  License

MIT License

---

##  Author

Venkatesh Mishra

Computer Vision • Machine Learning • Explainable AI
