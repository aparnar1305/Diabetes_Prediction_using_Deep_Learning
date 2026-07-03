# Diabetes Prediction using Deep Learning

A simple diabetes prediction model built using TensorFlow/Keras with a 62% accurate prediction.

## Dataset
- Pima Indians Diabetes Dataset

## Technologies Used
- Python
- TensorFlow/Keras
- NumPy
- Pandas

## Files
- `dltraining.py` - Trains the model and saves it.
- `diabetesprediction.py` - Loads the saved model and predicts diabetes.
- `model.json` - Model architecture.
- `model.weights.h5` - Trained weights.

## How to Run

1. Install dependencies

```bash
pip install -r requirements.txt
```

2. Train the model

```bash
python dltraining.py
```

3. Run prediction

```bash
python diabetesprediction.py
```
