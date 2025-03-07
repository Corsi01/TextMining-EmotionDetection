# Emotion Mapping through Text Mining

## Overview
This project explores emotion classification and clustering using the **GoEmotions dataset**, a collection of **Reddit comments** annotated with fine-grained emotional labels. The aim is to bridge emotion labels with psychological theory by mapping them into structured **Ekman categories** and **valence-based groups (positive, negative, ambiguous)**.

The study focuses on applying different **text representation techniques** and developing a **custom feature engineering approach** to capture emotional dimensions in text. Given the inherent challenges of sentiment analysis—where a deeper **semantic understanding** is often required—the results may be limited, but the project provides an extensive exploration of **fundamental NLP techniques** for emotion-based text analysis.

## Features
- 📝 **Dataset Processing**: Filtering and mapping fine-grained emotions into structured categories.
- 🔠 **Text Preprocessing**: Handling noise, slang, contractions, and emojis for standardization.
- 🔍 **Feature Engineering**: Using **TF-IDF, GloVe embeddings, and emotion lexicons** to enrich semantic understanding.
- 📊 **Exploratory Data Analysis**: Investigating patterns and relationships between emotions.

## Data Sources
- **[GoEmotions Dataset](https://github.com/google-research/google-research/tree/master/goemotions)** – 58,000+ Reddit comments labeled with 27 emotions.
- **NRC Emotion Lexicons** – Emotion intensity and valence information.
- **SenticNet** – Semantic and emotion-based word associations.
- **Pre-trained GloVe Embeddings** – Used to capture contextual word meanings.

## Methodology
### **1. Emotion Mapping**
🔹 **Ekman Mapping**: Groups emotions into six universal categories (joy, sadness, anger, etc.).  
🔹 **Valence Mapping**: Categorizes emotions into **positive, negative, and ambiguous** groups.

### **2. Text Preprocessing**
✔ Remove **noise** (URLs, emojis, excessive punctuation).  
✔ Normalize slang, contractions, and emoticons.  
✔ Apply **lemmatization** and **custom stopword filtering**.

### **3. Feature Engineering**
🔸 **TF-IDF Weighting**: Highlights important words in text.  
🔸 **GloVe Embeddings**: Captures contextual relationships.  
🔸 **Emotion Lexicons**: Integrates sentiment-specific features.

## Challenges & Future Improvements
✅ **Current Challenges**:
- Handling informal and ambiguous language in Reddit data.
- Addressing **class imbalance** in emotion distribution.

🚀 **Future Enhancements**:
- Implement **deep learning models (BERT, GPT)** for improved classification.
- Introduce **data augmentation** to balance emotional categories.
- Explore **alternative emotion lexicons** for richer sentiment features.

## License
MIT License © 2024 – Open-source contributions welcome!
