# Sleep Stage Classification using Machine Learning

## Overview
This project builds a machine learning classifier to identify different sleep stages (Wake, Light Sleep, Deep Sleep, REM) from EEG signal data. The model achieves **94% accuracy** on test data.

## Problem
Sleep stage classification is crucial for:
- Sleep disorder diagnosis
- Wearable device development (Oura Ring, Apple Watch, WHOOP)
- Clinical sleep research
- Mental health assessment

## Solution
I built a **Random Forest classifier** trained on EEG-like signals with the following approach:

1. **Data Generation**: Created 1,000 synthetic EEG samples across 4 sleep stages
2. **Feature Engineering**: Extracted 10 signal characteristics per sample
3. **Data Preprocessing**: Normalized features using StandardScaler
4. **Model Training**: Random Forest with 100 estimators
5. **Evaluation**: Comprehensive metrics and confusion matrix analysis

## Results

### Model Performance
- **Overall Accuracy**: 94.0%
- **Deep Sleep F1-Score**: 1.00 (perfect classification)
- **Light Sleep F1-Score**: 0.99
- **Wake F1-Score**: 0.88
- **REM F1-Score**: 0.87

## Tech Stack
- Python 3.9+
- scikit-learn, numpy, pandas, matplotlib, seaborn

## How to Run
```bash
pip install numpy pandas scikit-learn matplotlib seaborn jupyter
jupyter notebook
```

## Future Improvements
- Train on real EEG data from OpenNeuro or PhysioNet
- Implement deep learning models (CNN, LSTM)
- Add real-time classification pipeline
- Develop web interface for predictions

## Applications
- Wearable sleep tracking devices
- Clinical sleep disorder diagnosis
- Health app integration
- Sleep research

## License
MIT
