# Synthetic-Insulator-Generalization-Framework
# 🔌 Addressing Domain Shift in Insulator Defect Data: A Generalization Framework for Cross-Domain Detection of Broken and Self-Blast Insulator Defect
---

## 🚀 Overview

Accurate detection of insulator defects is critical for power system reliability.  
However, existing methods suffer from **domain shift** due to limited and non-diverse training datasets.  

We propose a **generalization framework** combining:
- **DR-Syn**: Synthetic insulator defect data generation via domain randomization.  
- **IR-IQA**: Instance-Reweighted Image Quality Assessment for robust style domain expansion.  
- **DCIL**: Discrepancy-Constrained Invariant Learning for feature-invariant training.  
- **Digital-Twin-Aided DR-Syn**: Prior-knowledge-based domain adaptation with real background scene modeling.  

---

## 📚 Generalization Framework

<img src="https://github.com/user-attachments/assets/a3feab73-f7b2-4eb9-8901-4601ba8954e5" alt="generalization_framework" width="50%" />

---

## 🏗️ DR-Syn Data Generation

<img src="https://github.com/user-attachments/assets/8b000e0e-272f-4cce-a81f-282bf59969c5" alt="dr_model_modified" width="100%" />

- Procedural disc material modeling  
- Domain randomization of insulator components & scene elements  
- Automatic annotation with ray-casting  
- Digital-twin-aided background modeling for domain adaptation  

---

## 🎨 Style Shift Mitigation

### IR-IQA Domain Expansion
<img src="https://github.com/user-attachments/assets/8a455ffd-551a-45ed-a9be-473f488d2e0c" alt="iriqa_revision" width="50%" />

- Preserves defect quality during strong style transfer  
- Weighted content loss for small insulator objects  
- Expands synthetic data into multiple domains  

### Discrepancy-Constrained Invariant Learning (DCIL)
<img width="2145" height="738" alt="dg_process" src="https://github.com/user-attachments/assets/7978c357-9465-4619-8f47-ef928e407dce" />

- Combines **IRM loss** and **Feature Discrepancy Minimization**  
- Ensures invariant feature representation across domains  

---

## 📊 Datasets

We curated multiple datasets, including real-world broken/self-blast insulators and synthetic datasets from DR-Syn.  

<img src="https://github.com/user-attachments/assets/45534202-0beb-4077-af7b-673de7268e2b" alt="dataset_visualization" width="50%" />

---

## 🔍 Feature Space Visualization

<img src="https://github.com/user-attachments/assets/dc5c3b6c-3ffd-41c9-918b-8c6fa720d438" alt="DCIL_feature_maps" width="50%" />





