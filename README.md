# Audio-Genre-Classification-using-Deep-Learning-
This project investigates deep learning techniques for audio genre classification on the GTZAN and FMA Small datasets.

## Models
The following models were implemented and evaluated:

Convolutional Neural Network (CNN)
Long Short-Term Memory (LSTM)
Vision Transformer (ViT)
## Features
Audio features extracted:

Mel Spectrograms
Mel Frequency Cepstral Coefficients (MFCCs)
## Datasets
GTZAN - 10 genres, 1000 30-second audio clips
FMA Small - 8 genres, 8000 full-length tracks
## Results
CNN achieved 72% accuracy on GTZAN and 48% on FMA Small with Mel Spectrograms
LSTM achieved 81% accuracy on GTZAN with MFCCs
ViT struggled to match CNN performance, peaking at 41% accuracy on FMA Small
## Conclusion
CNN and LSTM models show promise for audio classification. MFCCs effective for LSTM. ViT needs improvement. Feature extraction and model selection significantly impact performance.

## References
Choi et al. (2018), Dieleman et al. (2016), Dai et al. (2016), Hafizah et al. (2021), Lee et al. (2017), Tian et al. (2017), Tzanetakis & Cook (2002)

## Usage
See GitHub repository for model code and documentation. Dataset links provided within.
