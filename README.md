<img width="434" height="1117" alt="LuminaSkin 3- Research Prototype" src="https://github.com/user-attachments/assets/41227fb3-3a18-48e0-a3bb-01d425058e77" />
# Poultry Guard AI | Computer Vision for Precision Agriculture

Poultry Guard is an AI-driven monitoring system that leverages **Object Detection** to enhance biosecurity and flock management. By identifying health anomalies and behavioral patterns in real-time, the system provides actionable insights to reduce operational risks in poultry farming.

## 🚀 Key Features
* **Real-time Health Monitoring:** Detection of lethargic or symptomatic behavior in flocks.
* **Anomaly Detection:** Immediate alerts for environmental or behavioral irregularities.
* **Scalable Data Insights:** Designed for deployment in resource-constrained agricultural environments.

## 🛠️ Technical Stack
* **Core:** Python
* **Model:** YOLO (You Only Look Once) / TensorFlow (specify which one you used)
* **Dataset:** Custom-annotated poultry health imagery.
* **Goal:** Edge AI deployment for real-time farm diagnostics.

## 🎓 Research Context
This project was developed at **Nnamdi Azikiwe University (UNIZIK)** as part of my focus on applying **Computer Vision** to high-impact, real-world problems. It serves as a core component of my portfolio for graduate research applications at institutions like **GIST** and **POSTECH**.
## 🎨 UI/UX & Research Implementation

### High-Fidelity Diagnostic Dashboard
The current iteration of the LuminaSkin interface focuses on **Longitudinal Data Analysis** and **Clinical Context**. By moving beyond a simple classification output, the UI now supports a clinician's workflow by providing historical comparisons and patient metadata.

#### Key Features:
* **Temporal Tracking:** Implementation of a horizontal carousel to monitor lesion evolution over time, utilizing unique `patient_id` strings from the ISIC Archive.
* **Clinical Metadata Integration:** Displays essential patient context including age, anatomical site, and image acquisition type (Dermoscopic) to reduce diagnostic bias.
* **Heuristic Alignment:** Follows standard medical software design patterns to ensure high scannability and low cognitive load during analysis.

#### Data Provenance
Images and metadata used in these prototypes are sourced from the **ISIC (International Skin Imaging Collaboration) Archive**, ensuring that the UI is grounded in real-world dermatological research data.

| Feature | Status | Description |
| :--- | :--- | :--- |
| Image Analysis | ✅ Complete | 98% Confidence score display |
| History View | ✅ Complete | Horizontal scroll for past scans |
| Metadata | ✅ Complete | Patient context & ISIC ID tracking |
*Developed by peace*
