NLP Emotion Classification Project

Multi-class emotion classification on tweet dataset using Neural Networks.

## Project Overview

This project classifies tweets into 6 emotions: **anger, fear, joy, love, sadness, surprise**

## Models Implemented

| Model | Architecture | Test Accuracy |
|-------|-------------|---------------|
| Model 1 | Fully Connected NN (TF-IDF) | 86.30% |
| Model 2 | Bidirectional LSTM | **90.20%** Best Model |
| Model 3 | Transformer-style (Attention) | 87.50% |

## Best Model: Bidirectional LSTM (90.20%)


### Prerequisites
```bash
pip install -r requirements.txt
```

### Run the Project
```bash
jupyter notebook nlpml.ipynb
```

## Results

### Model Comparison

- **FCNN**: Fast baseline, loses word order
- **LSTM**: Best performance, captures sequential patterns
- **Transformer**: Good balance, attention mechanism

### Key Insights

1. Word order matters for emotion classification  
2. Bidirectional LSTM captures context best  
3. Sequential models outperform bag-of-words  
4. Dropout prevents overfitting effectively

## Technologies Used

- Python 3.12
- TensorFlow/Keras
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn

## Dataset

Emotion-labeled tweets dataset  
- 6 emotion classes
- Train/Test/Validation split

## Author

**Iqra Javed**  
[https://github.com/IqraJavedd] | [https://drive.google.com/file/d/1UYWr-558un_9B5b41xi1AGb0sckjkKIO/view?usp=sharing]

