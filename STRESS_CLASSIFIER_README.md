# Mental Health & Stress Level Prediction

## Overview
This project builds a machine learning classifier to predict stress levels (Low, Medium, High) based on Canadian health survey data with **71.81% accuracy**.

## Problem
Understanding stress patterns and their predictors is crucial for:
- Mental health intervention
- Workplace wellness programs
- Public health research
- Healthcare resource allocation

## Solution
I built a **Random Forest classifier** trained on 108K+ Canadian health survey responses.

### Key Findings
- **Work stress** is the strongest predictor of overall stress (15.6% importance)
- **Life satisfaction** is the second most important factor (10.0% importance)
- **Mental health state** strongly correlates with stress levels (8.2% importance)
- Income and anxiety disorder status also significantly predict stress

## Results

### Model Performance
- **Overall Accuracy**: 71.81%
- **Low Stress Classification**: High precision and recall
- **Medium Stress Classification**: Balanced performance
- **High Stress Classification**: Reliable detection

## Tech Stack
- Python 3.9+
- scikit-learn, pandas, numpy
- matplotlib, seaborn
- Jupyter Notebook

## Dataset
- Source: Canadian Health Survey (2019-2020)
- Size: 108,252 respondents, 50 health and lifestyle features
- Real government health data

## Features Used
- Work stress levels
- Life satisfaction rating
- Mental and general health state
- Physical activity levels
- Income and employment status
- Medical conditions (anxiety, mood disorders, etc.)
- Lifestyle factors (smoking, alcohol, diet)

## Future Improvements
- [ ] Deploy as web app for stress assessment
- [ ] Add personalized recommendations
- [ ] Integrate with wearable health data
- [ ] Develop intervention tracking system
- [ ] Extend to other mental health conditions

## Applications
- Workplace mental health programs
- Healthcare screening tools
- Public health research
- Clinical decision support
- Wellness app integration

## License
MIT
