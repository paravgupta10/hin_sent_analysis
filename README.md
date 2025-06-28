# Hindi Sentiment Analysis using Transformers

This project implements a **Hindi sentiment classification system** using a custom **Transformer-based deep learning model** with **IndicBERT tokenizer**. The model classifies input Hindi text into three categories: **Negative**, **Neutral**, or **Positive**.

## 📊 Dataset
- Source: Labeled Hindi text samples (Excel format)
- Classes: `0 = Negative`, `1 = Neutral`, `2 = Positive`
- Train size: 1,470 samples
- Test size: 367 samples

## 🧠 Methodology
- **Tokenizer**: `ai4bharat/indic-bert`
- **Model**: Custom Transformer with positional encoding and attention pooling
- **Training**: 100 epochs using Adam optimizer and CrossEntropyLoss


