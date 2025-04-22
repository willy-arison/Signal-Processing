# Signal-Processing
# Wheezing Detection Using Audio Signal Processing

This project aims to classify breathing sounds as either **normal** or **wheezing**—a common symptom in asthmatic patients. The model uses a 1D Convolutional Neural Network (CNN) trained on Mel-frequency cepstral coefficients (MFCCs) extracted from audio signals.

## Project Structure
- **Normal/**: Contains audio recordings of healthy breathing sounds.
- **Wheezing/**: Contains audio recordings of abnormal breathing with wheezing.

## Methodology
1. **Feature Extraction**:  
   - Uses the `librosa` library to extract MFCCs from audio signals.
2. **Model Architecture**:  
   - A 1D CNN trained to classify breathing sounds based on extracted features.
3. **Expected Outcome**:  
   - The model accurately distinguishes between normal and wheezing breathing, assisting in early asthma detection or respiratory health monitoring.

## Requirements
- Python 3
- Libraries: `librosa`, `torch`, `numpy`, `matplotlib`, `scikit-learn`

## Results
- **Test Accuracy**: ~95.74%
- **Classification Report**:  
  - Precision/Recall for Normal: 0.944  
  - Precision/Recall for Wheezing: 0.966  
