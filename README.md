# 🍽️ Sentiment Analysis of Restaurant Reviews

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-NLP-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

A **Natural Language Processing (NLP)** project that analyzes restaurant reviews and classifies them as **Positive** or **Negative** using Machine Learning techniques.

This project demonstrates an end-to-end **text classification pipeline**, including data preprocessing, feature extraction, model training, and evaluation.

---

# 📌 Project Overview

Customer reviews contain valuable insights about restaurant experiences.
This project uses **Natural Language Processing (NLP)** to automatically detect whether a review expresses **positive or negative sentiment**.

The model processes raw text reviews and converts them into numerical features using the **Bag of Words model**, then trains a **Naive Bayes classifier** to perform sentiment classification.

---

# ⚙️ Tech Stack

| Technology   | Purpose                        |
| ------------ | ------------------------------ |
| Python       | Core programming language      |
| NumPy        | Numerical operations           |
| Pandas       | Data handling                  |
| NLTK         | Natural Language Processing    |
| Scikit-learn | Machine learning model         |
| Matplotlib   | Data visualization             |
| Seaborn      | Confusion matrix visualization |

---

# 🧠 Machine Learning Pipeline

### 1️⃣ Data Loading

Load the restaurant review dataset using Pandas.

### 2️⃣ Text Preprocessing

* Remove punctuation and special characters
* Convert text to lowercase
* Remove stopwords
* Apply stemming using **Porter Stemmer**

### 3️⃣ Feature Extraction

Convert text into numerical vectors using:

**Bag of Words (CountVectorizer)**

### 4️⃣ Train/Test Split

Split the dataset into **training and testing sets**.

### 5️⃣ Model Training

Train a **Naive Bayes classifier** on the processed text data.

### 6️⃣ Model Evaluation

Evaluate the model using a **confusion matrix** and visualization.

---

# 📊 Model Evaluation

The confusion matrix helps analyze model performance.

| Actual / Predicted | Negative | Positive |
| ------------------ | -------- | -------- |
| Negative           | TN       | FP       |
| Positive           | FN       | TP       |

A heatmap visualization is generated using **Seaborn** to better understand classification results.

---

# 📂 Project Structure

```
Sentiment-Analysis-Restaurant-Reviews
│
├── Restaurant_Reviews.tsv
├── Sentiment Analysis of Restaurant Reviews.ipynb
├── README.md
└── requirements.txt
```

---

# 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/sentiment-analysis-restaurant-reviews.git
```

---

### 2️⃣ Navigate to the Project Folder

```
cd sentiment-analysis-restaurant-reviews
```

---

### 3️⃣ Create Virtual Environment

```
python -m venv venv
```

---

### 4️⃣ Activate Virtual Environment

Windows:

```
venv\Scripts\activate
```

---

### 5️⃣ Install Dependencies

```
pip install -r requirements.txt
```

---

### 6️⃣ Run the Notebook

```
jupyter notebook
```

Open the notebook and execute the cells to see the results.

---

# 📚 Key Concepts Used

* Natural Language Processing (NLP)
* Text Cleaning
* Stopword Removal
* Stemming
* Bag of Words
* Machine Learning Classification
* Confusion Matrix
* Data Visualization

---

# 🎯 Learning Outcomes

This project helped in understanding:

* How **text data is preprocessed for NLP**
* Feature extraction using **Bag of Words**
* Training **machine learning classifiers**
* Evaluating models using **confusion matrices**
* Visualizing results using **Seaborn heatmaps**

---

# 🔮 Future Improvements

Possible improvements for this project:

* Use **TF-IDF Vectorization**
* Train advanced models like **Logistic Regression or SVM**
* Implement **Deep Learning (LSTM / BERT)** for better accuracy
* Deploy the model as a **web application**

---

# 👨‍💻 Author

**Shivam Mishra**

🎓 BTech Student
💻 Aspiring Software Developer
🤖 Interested in AI, Machine Learning, and Backend Development

---

⭐ If you like this project, consider **starring the repository** to support the work!
