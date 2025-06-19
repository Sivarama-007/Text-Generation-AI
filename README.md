# 🧠 Text Generation AI – Next Word Prediction

This project builds a deep learning model to **predict the next word** in a sequence and **generate new text** using LSTM-based neural networks. The model is trained on real-world news content from the `fake_or_real_news.csv` dataset.

---

## 🚀 Project Goal

- **Train an LSTM model** to predict the next word in a sentence.
- Use the model to **generate text** starting from a seed input.
- Handle large data efficiently within limited compute environments (like Google Colab).

---

## 📂 Dataset

- **Name**: `fake_or_real_news.csv`
- **Size**: ~29 MB
- **Used Column**: `text` (news article content)
- **Source**: Kaggle / Public domain

---

## 🧰 Tools & Libraries

- Python 3.x
- TensorFlow / Keras
- NumPy, Pandas, Matplotlib
- NLTK (for tokenization)

Install requirements using:

```bash
pip install tensorflow pandas numpy matplotlib nltk
