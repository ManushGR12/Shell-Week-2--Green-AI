# Shell-Week-2--Green-AI
Model Training is done in this repo

# Org Go - Model Training

This repository contains Jupyter notebooks and scripts for training machine learning models using preprocessed agricultural data from the Org Go data repository.

## 📁 Repository Structure

- `notebooks/01_model_training_xgboost.ipynb` - XGBoost model training notebook
- `models/` - Folder to save trained model files (`.model`, `.pkl`, etc.)
- `requirements.txt` - Python dependencies including XGBoost
- `.gitignore` - Excludes large model files and sensitive info

## 🚀 Getting Started

1. Clone the Org Go Data repo and preprocess your datasets.
2. Install required packages:
3. Place the processed train/test datasets from the Data repo in a directory accessible to this repo.
4. Open and run the training notebook:


## 🧠 Model Training Details

- Train an XGBoost classifier on the crop recommendation dataset
- Evaluate accuracy and generate classification reports
- Save the trained model for later inference or deployment

## 📦 Outputs

- Trained XGBoost model saved to `models/xgboost_crop_recommendation.model`
- Performance metrics printed in the notebook

## 🔗 Next Steps

- Extend with additional models for price prediction, yield, or disease detection
- Integrate the trained model into a web or mobile application

## 📄 License

This project is licensed under the MIT License.
