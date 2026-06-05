# Cervical Cytology Classifier

Deep learning model for automated cervical cell classification 
using the SIPaKMeD dataset. Built with PyTorch, transfer learning 
(ResNet50/EfficientNet), and Grad-CAM explainability.

## Dataset
SIPaKMeD — 4,049 cervical cell images across 5 classes.

Download via Kaggle API:
kaggle datasets download -d prahladmehandiratta/cervical-cancer-largest-dataset-sipakmed
unzip cervical-cancer-largest-dataset-sipakmed.zip -d data/sipakmed

## Project Structure
notebooks/     — one notebook per phase
results/       — plots, metrics, Grad-CAM outputs

## Status
- [x] Phase 1: Data acquisition
- [ ] Phase 2: EDA
- [ ] Phase 3: Preprocessing
- [ ] Phase 4: Model training
- [ ] Phase 5: Evaluation & Grad-CAM
- [ ] Phase 6: Deployment
