# Parkinson-s-Disease-Detection-via-Vocal-Biomarkers
🎙️ Parkinson's Disease Detection via Vocal Biomarkers
This project focuses on the early recognition of Parkinson's Disease (PD) using vocal biomarkers extracted from speech recordings. Parkinson’s often affects speech production, introducing subtle changes in voice that can be detected through acoustic analysis. This system leverages both traditional and nonlinear features to build a robust machine learning model capable of distinguishing between healthy individuals and PD patients.

🔍 Key Features:
Vocal Feature Extraction using the Parselmouth library (Praat interface) for standard features like Jitter and Shimmer.

Advanced Nonlinear Features:

Detrended Fluctuation Analysis (DFA) via the Fathon library for capturing long-term correlations.

Recurrence Period Density Entropy (RPDE) using pyRPDE for quantifying recurrence unpredictability in speech.

Pitch Period Entropy (PPE) following the approach proposed by Little et al. for pitch regularity analysis.

Machine Learning Classification to predict Parkinson’s status based on extracted features.

Designed for reproducibility, accuracy, and interpretability.

📦 Technologies Used:
Python (NumPy, SciPy, Scikit-learn, Pandas, Matplotlib)

Parselmouth (Praat)

Fathon

pyRPDE
