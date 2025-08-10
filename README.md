# 📩 SMS Spam Classifier

An end-to-end **machine learning application** that classifies SMS messages as **Spam** or **Ham** (not spam).  
Built with **Python**, **scikit-learn**, and **Streamlit**, it uses the **Multinomial Naïve Bayes** algorithm and text vectorization to make real-time predictions.

---

## 🚀 Features
- Detects spam messages with high accuracy.
- Preprocesses and vectorizes text using **CountVectorizer**.
- Uses **Multinomial Naïve Bayes** for classification.
- Interactive **Streamlit** web interface.
- Lightweight and fast — instant predictions.

---

## 🛠 Technologies Used
- **Python**
- **scikit-learn**
- **Pandas** & **NumPy**
- **Streamlit**

---

## 📂 Project Structure
```

├── train\_model.py       # Preprocesses data, trains model, saves .pkl files
├── app.py               # Streamlit app for predictions
├── spam.csv             # Dataset
├── spam\_model.pkl       # Saved trained model
├── vectorizer.pkl       # Saved text vectorizer
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation

````

---

## ⚙️ How to Run Locally

1️⃣ **Clone this repository**  
```bash
git clone https://github.com/yourusername/sms-spam-classifier.git
cd sms-spam-classifier
````

2️⃣ **Install dependencies**

```bash
pip install -r requirements.txt
```

3️⃣ **Train the model (only needed once)**

```bash
python train_model.py
```

4️⃣ **Run the Streamlit app**

```bash
streamlit run app.py
```

---

## 📊 How It Works

1. Loads and preprocesses the SMS dataset.
2. Converts text into numerical features with **CountVectorizer**.
3. Trains the **Multinomial Naïve Bayes** model.
4. Saves the trained model and vectorizer for later use.
5. Streamlit app loads them to make instant predictions.

---

## 📜 License

This project is licensed under the MIT License — feel free to use and modify.

---

## 🙌 Acknowledgements

* [scikit-learn](https://scikit-learn.org/)
* [Streamlit](https://streamlit.io/)
* [UCI SMS Spam Collection Dataset](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection)

```

---

If you want, I can also make this **README visually attractive** with emojis in section headers and maybe a **screenshot of the app** so it catches attention on GitHub.  
Do you want me to do that?
```

