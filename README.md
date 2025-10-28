# 📰 Fake News Predictor

A Machine Learning project that predicts whether a given news article is **Fake** or **Real** using Natural Language Processing (NLP) techniques and Logistic Regression.

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
├── fake_news_predictor.ipynb # Colab / Jupyter notebook for model training
├── requirements.txt # Python dependencies
├── .gitignore # To prevent large data files from being pushed
└── README.md


---

## 📦 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Madhu-014/Fake-News-Predictor.git
cd Fake-News-Predictor

Create and Activate a Virtual Environment (recommended)
# For Windows
python -m venv venv
venv\Scripts\activate

# For macOS / Linux
python3 -m venv venv
source venv/bin/activate

Install Dependencies
pip install -r requirements.txt

📊 Dataset

The dataset used in this project comes from Kaggle - https://www.kaggle.com/datasets/emineyetm/fake-news-detection-datasets