TO VIEW THE PPT FILE
[https://docs.google.com/presentation/d/1FE7fYDuLmM1jdJimunBgdEGb1Ppx9TW-/edit?usp=drive_link&ouid=108215915749467567227&rtpof=true&sd=true](url)

OR

Click View Raw after selecting the Final year Presentation.pptx to view the PowerPoint Presentation file.

---

# Developing a Predictable and Explainable Model for Cardiovascular Diseases

## Overview
Cardiovascular diseases (CVDs) are among the leading causes of mortality worldwide. This project focuses on creating predictive and explainable models for diagnosing CVDs to enhance medical decision-making. By leveraging cutting-edge machine learning techniques and explainable AI (XAI), the research aims to improve diagnosis accuracy and provide actionable insights for healthcare professionals.

---

## Table of Contents
- [Abstract](#abstract)
- [Features](#features)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)
- [Conclusion and Future Work](#conclusion-and-future-work)
- [Team](#team)
- [References](#references)

---

## Abstract
This project developed:
1. An ensemble predictive model using ECG data with **93.11% accuracy** for early detection of right ventricle abnormalities.
2. A cardiovascular disease model from a dataset of 70,000 patient records integrated with **LIME (Local Interpretable Model-Agnostic Explanations)**, achieving **88.15% accuracy**.
3. Advanced diagnostic tools incorporating XAI to improve decision-making and patient care efficiency.

---

## Features
- **High Predictive Accuracy**: Models optimized using advanced ensemble techniques.
- **Explainable AI**: Integration of XAI for interpretability of predictions.
- **Focus on Right Ventricular Deformation**: Enhanced accuracy for specific conditions.
- **Comparative Analysis**: Evaluation against traditional ML and pre-trained models.
- **Data Visualization**: Correlation matrix, ROC curves, and other key visualizations.

---

## Dataset
### Data Sources:
- Cleveland, Hungary, Switzerland, and Long Beach V datasets.
- Heart Statlog Cleveland Hungary dataset.

### Key Features:
- **Objective**: Age, Height, Weight, Gender.
- **Examination**: Systolic BP, Diastolic BP, Cholesterol, Glucose.
- **Subjective**: Smoking, Alcohol intake, Physical activity.
- **Target Variable**: Presence of cardiovascular disease (binary).

---

## Methodology
### A. Ensemble Model:
- **Phase 1**: Voting classifier combining predictions from multiple models.
- **Phase 2**: Advanced ensemble techniques for improved accuracy.

### B. Explainable AI Model:
- Utilized LIME to provide interpretable insights for clinicians.
- Workflow integrated ECG data and other medical features.

![Ensemble Model Workflow](#)  
![XAI Model Workflow](#)

---

## Results
- **Improved Accuracy**: Ensemble model achieved **88.15% accuracy**, outperforming traditional and pre-trained models.
- **Interpretability**: XAI provided clear feature importance for predictions.
- **Visualization**:
  - **Confusion Matrix**: Model performance on test data.
  - **Precision-Recall Curve**: Evaluation of sensitivity and specificity.
  - **ROC Curve**: Performance comparison among models.

![Model Accuracies Comparison](#)  
![Features Impact of Patient](#)

---

## Conclusion and Future Work
### Conclusion:
- The ensemble and XAI models significantly enhance prediction accuracy and explainability.
- Early detection and personalized patient care are made feasible using these models.

### Future Work:
1. Expand datasets to include diverse populations and additional features like genetic predispositions.
2. Develop standardized protocols for CMRI data acquisition.
3. Improve interpretability further for real-time clinical applications.

---

## Team
- **Prem Babu Kanaparthi**  
- **Rahul Golla**  
- **Sai Hemander Kambhampati**

**Supervisor**: Dr. Biswajit Purkayastha, Professor, Department of Computer Science and Engineering, NIT Silchar.

---

## References
1. [WHO Fact Sheets on CVDs](https://www.who.int/news-room/fact-sheets/detail/cardiovascular-diseases-(cvds))
2. Yifeng Gao et al., "Deep learning-based prognostic model..." European Radiology, 2023.
3. [Nature: Post-COVID CVD Trends](https://www.nature.com/articles/d41586-022-02074-3)

For a full list of references, see the `References` section in the [presentation]
