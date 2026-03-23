# EEG-User-Authentication
EEG-based user authentication system leveraging temporal and spatial brain signal features. Implements signal processing and machine learning for secure and reliable biometric identification.

# EEG-Based User Authentication System

## Project Title

**User Authentication using EEG Signal Analysis**

---

## Overview

This project presents a secure biometric authentication system using **Electroencephalogram (EEG) signals**. Unlike traditional authentication methods such as passwords or fingerprints, EEG signals are highly unique and difficult to replicate, making them a robust alternative for identity verification.

---

## Abstract

Electroencephalogram (EEG) signals provide a highly secure biometric modality due to their uniqueness and resistance to replication, as they originate from internal brain activity. This project presents an EEG-based user authentication system that analyzes both temporal and spatial characteristics of brain signals.

The raw EEG data is preprocessed through filtering and segmentation, followed by feature extraction using frequency band analysis (delta, theta, alpha, beta, and gamma) and inter-signal relationships. These features are combined to develop a robust classification model for user identification.

Experimental results demonstrate that spatial features significantly enhance authentication performance, while their combination with temporal features further improves system reliability and accuracy.

---

## Objective

* Develop a biometric authentication system using EEG signals
* Extract meaningful features from brainwave data
* Apply machine learning techniques for user identification

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Signal Processing
* Machine Learning

---

## Methodology

1. EEG Signal Acquisition
2. Preprocessing (Filtering & Noise Removal)
3. Signal Segmentation
4. Feature Extraction:

   * Frequency Bands (Delta, Theta, Alpha, Beta, Gamma)
   * Spatial & Temporal Features
5. Model Training & Classification
6. User Authentication

---

## Dataset

The dataset used in this project is approximately **10 GB in size** and is not included in this repository due to storage limitations.

🔗 Dataset Link: https://physionet.org/content/auditory-eeg/1.0.0/

### Instructions

1. Download the dataset from the above link
2. Create a folder named `dataset/`
3. Place all dataset files inside this folder
4. Update file paths in the notebook if required

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Snigdha-saxena08/EEG-User-Authentication.git
```

2. Install dependencies:

```bash
pip install numpy pandas matplotlib scikit-learn
```

3. Open the notebook:

* Use Jupyter Notebook or Google Colab

---

## How to Run

1. Ensure dataset is placed in the `dataset/` folder
2. Open `Brainwave_Authentication.ipynb`
3. Run all cells sequentially
4. Analyze outputs and model performance

---

## Results

* Achieved reliable classification accuracy using EEG features
* Spatial features showed strong performance in distinguishing users
* Combining temporal and spatial features improved system accuracy and robustness

---

## Future Scope

* Integration with real-time EEG devices
* Use of deep learning models (CNN, RNN)
* Multi-factor authentication systems
* Deployment as a secure login system

---

## Author

**Snigdha Saxena**

---

## Acknowledgment

I would like to express my sincere gratitude to **Dr. Abhilasha Sharma** for guidance and support throughout this project.

---

## References

1. M. Aldayel, N. Alsedairy, and A. Al-Nafjan, *"Brainwave Biometrics: A Secure and Scalable Brain–Computer Interface-Based Authentication System,"* AI, 2025.

2. *"EEGAuth: A Secure and Lightweight EEG-Based System Integrating Authentication and Key Generation,"* 2025.

3. *"A Brainwave Verification System Integrating Passwords with EEG Templates for Online Identification and Authentication,"* 2025.

4. M. Fallahi, P. Arias-Cabarcos, and T. Strufe, *"Beyond Gaze Points: Augmenting Eye Movement with Brainwave Data for Multimodal User Authentication in Extended Reality,"* 2024.

5. *"BrainAuth: A Neuro-Biometric Approach for Personal Authentication,"* 2023.

6. *"Brainwave-Based Authentication Using Features Fusion,"* 2023.

7. PhysioNet, *"Auditory EEG Dataset."*
   https://physionet.org/content/auditory-eeg/1.0.0/

---

## License

This project is for academic and educational purposes only.

---
