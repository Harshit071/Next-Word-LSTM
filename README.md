# Next Word Prediction with LSTM (Streamlit App)

This project is a web app for next word prediction using an LSTM neural network, built with TensorFlow/Keras and Streamlit. The model is trained on Shakespeare's Hamlet.

## Features

- Predicts the next word in a sequence using a trained LSTM model
- Simple web interface built with Streamlit
- Ready for local use or deployment on [Streamlit Community Cloud](https://streamlit.io/cloud)

## Setup

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
```

### 2. Create and activate a conda environment

```bash
conda create -n lstm_tf_compat python=3.10 -y
conda activate lstm_tf_compat
```

### 3. Install dependencies

```bash
pip install tensorflow==2.13.0 numpy pandas scikit-learn matplotlib tensorboard streamlit scikeras
```

### 4. Run the app

```bash
streamlit run app.py
```

## Files

- `app.py` — Streamlit web app
- `next_word_lstm.h5` — Trained LSTM model
- `tokenizer.pickle` — Tokenizer for text preprocessing
- `hamlet.txt` — Training data (Shakespeare's Hamlet)
- `requirements.txt` — Python dependencies

## Deployment

You can deploy this app for free on [Streamlit Community Cloud](https://streamlit.io/cloud):

1. Push your code to a public GitHub repository.
2. Go to [Streamlit Cloud](https://streamlit.io/cloud) and click "New app".
3. Connect your repo and select `app.py` as the entry point.
4. Make sure your `requirements.txt` (and model/tokenizer files) are in the repo.

## License

MIT License 