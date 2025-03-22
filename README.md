# NER Dataset Preprocessing (PLOD-CW-25)

This project contains data preprocessing steps for Named Entity Recognition (NER) using the PLOD-CW-25 dataset.

## Folder Structure

- `notebooks/`: Colab notebooks for data cleaning & feature extraction
- `preprocess/`: Saved `.pkl` feature files for CRF/HMM models

## Tools Used
- Python, Pandas, Joblib
- Google Colab
- PLOD-CW-25 dataset

## How to Use
1. Open the notebook in `notebooks/`
2. Run cells to load and clean the data
3. Load `.pkl` files from `preprocess/` to train CRF/HMM models

## Team
- Min – Dataset Preprocessing
- Vladimir – CRF/HMM Modeling
- Manikarnika – BERT Fine-tuning
