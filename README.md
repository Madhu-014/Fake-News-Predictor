# 📰 Fake News Predictor

A Machine Learning project that predicts whether a given news article is **Fake** or **Real** using **Natural Language Processing (NLP)** techniques and **Logistic Regression**.

---

## 🚀 Try It on Google Colab
You can run this project directly on Colab without any local setup:  
👉 [**Open in Google Colab**](https://colab.research.google.com/drive/1V6HJIv7YEMOU61c6fuJ3apxpNNTHCjes?usp=sharing)

---

## 📁 Project Structure

```text
Fake-News-Predictor/
├── data/                     # Folder to store raw Kaggle dataset (ignored in Git)
│   ├── True.csv
│   └── Fake.csv
├── processed/                # Folder for processed train/test/validation datasets
│   ├── train.csv
│   ├── test.csv
│   └── valid.csv
├── fake_news_predictor.ipynb # Jupyter / Colab notebook for model training
├── requirements.txt          # Python dependencies
├── .gitignore                # To prevent large data files from being pushed
└── README.md
⚙️ Installation & Setup
1️⃣ Clone the Repository
bash
Copy code
git clone https://github.com/Madhu-014/Fake-News-Predictor.git
cd Fake-News-Predictor
2️⃣ Create and Activate a Virtual Environment (Recommended)
For Windows

bash
Copy code
python -m venv venv
venv\Scripts\activate
For macOS / Linux

bash
Copy code
python3 -m venv venv
source venv/bin/activate
3️⃣ Install Dependencies
bash
Copy code
pip install -r requirements.txt
📊 Dataset
The dataset used in this project comes from Kaggle:
🔗 Fake News Detection Datasets by Emine YETMİŞ

Steps to Download:
Visit the Kaggle link above.

Click on “Download” to get the ZIP file.

Extract it and move the following two files into the data/ folder:

text
Copy code
data/
├── True.csv
└── Fake.csv

Then create a processed folder where your train,test and val data will be stored.

You are all set
