# 🌾 Crop Recommendation System (ANN - scikit-learn MLP)

A fast, deployable neural net (MLPClassifier) that recommends crops from soil & weather inputs.

## Results (this build)
- Test Accuracy: 0.9697

## Files
- `app.py` — Streamlit web app
- `requirements.txt` — dependencies
- `artifacts/` — trained assets
  - `model.joblib`
  - `scaler.joblib`
  - `label_encoder_classes.json`

## Run locally
```
pip install -r requirements.txt
streamlit run app.py
```

## Deploy
- Streamlit Community Cloud or Hugging Face Spaces. Point to `app.py`.
