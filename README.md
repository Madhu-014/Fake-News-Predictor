# 📰 Fake News Predictor

A Machine Learning project that predicts whether a given news article is **Fake** or **Real** using **Natural Language Processing (NLP)** techniques and **Logistic Regression**.

---

## 🚀 Try It on Google Colab
You can run this project directly on Colab without any local setup:  
👉 [**Open in Google Colab**](https://colab.research.google.com/drive/1V6HJIv7YEMOU61c6fuJ3apxpNNTHCjes?usp=sharing)

---

## 📁 Project Structure

Fake-News-Predictor/
├── data/ # Folder to store raw Kaggle dataset (ignored in Git)
│ ├── True.csv
│ └── Fake.csv
├── processed/ # Folder for processed train/test/validation datasets
│ ├── train.csv
│ ├── test.csv
│ └── valid.csv
├── fake_news_predictor.ipynb # Jupyter / Colab notebook for model training
├── requirements.txt # Python dependencies
├── .gitignore # To prevent large data files from being pushed
└── README.md

yaml
Copy code

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
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

Click on "Download" to get the ZIP file.

Extract it and move the following two files into the data/ folder:

graphql
Copy code
data/
├── True.csv
└── Fake.csv
🧱 Data Preparation
Once the raw CSV files are in the data/ folder, prepare the dataset by running:

bash
Copy code
python prepare_dataset.py
This will:

Merge the True.csv and Fake.csv files

Shuffle and label the data

Split it into train.csv, test.csv, and valid.csv

Save them inside the processed/ folder

✅ You’ll see:

pgsql
Copy code
processed/
├── train.csv
├── test.csv
└── valid.csv
