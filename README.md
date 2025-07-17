

## 🎵 Music Recommendation System (Content-Based)

This project is a **Content-Based Music Recommendation System** built in a **Jupyter Notebook** using **Python**, **pandas**, **scikit-learn**, and **NLTK**.

It recommends songs by analyzing their content (like lyrics and artist) and suggesting the most similar ones.

---

### 📌 Features

* Content-based filtering using **TF-IDF Vectorization**
* Text cleaning with **NLTK**
* Similarity calculated via **cosine similarity**
* Lightweight and easy to understand

---

### 📁 Files

```
music-recommender/
│
├── Music_Recommendation.ipynb  # Main Jupyter Notebook
├── songs.csv                   # Dataset of songs
├── requirements.txt            # Python dependencies
└── README.md                   # Project info
```

---

### 📦 Installation

Make sure you have Python installed (preferably 3.7+). Then install the dependencies:

```bash
pip install -r requirements.txt
```

Also download required NLTK resources once:

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

---

### 📊 Dataset Format

`songs.csv` should have at least the following columns:

* `title` – Song title
* `artist` – Artist name
* `lyrics` – Song lyrics

Example:

```csv
title,artist,lyrics
Hello,Adele,"Hello, it's me..."
```

---

### 🚀 How to Use

1. Open the `Music_Recommendation.ipynb` notebook.
2. Run the cells step by step.
3. Use the `recommend(song_title)` function to get similar songs.

```python
recommend("Shape of You")
```

---

### 🛠 Libraries Used

* `pandas`
* `scikit-learn`
* `nltk`

---

