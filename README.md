# Sentiment Analysis of Shopee App Reviews

The main purpose of developing this sentiment analysis project is to fulfill the final capstone requirement of the **Machine Learning Development** learning path provided by **Dicoding**.  

In addition, this project was built using **Jupyter Notebook** and **Python** to demonstrate the application of **Natural Language Processing (NLP)** and supervised machine learning in understanding people's perception of the Shopee mobile app through user reviews.

---

## Project Structure:
```
ANALISIS_SENTIMEN_SHOPE/
│
├── HASIL DATA SCRAPING/
│   └── Ulasan_SHOPEE.csv               # Collected reviews scraped from the Shopee app
│
├── PELATIHAN MODEL/
│   ├── MODEL_A387YBM185.ipynb           # Model building and sentiment classification notebook
│   └── MODEL_A387YBM185.py              # Python script version for training
│
├── SCRAPING DATA/
│   ├── SCRAPING_A387YBM185.ipynb        # Notebook for scraping Shopee reviews
│   └── SCRAPING_A387YBM185.py           # Script to automate scraping
│
├── REQUIREMENTS.csv                       # CSV list of libraries
├── REQUIREMENTS.txt                       # Python packages and dependencies used
```

---

## Prerequisites

Ensure you have **Python 3.8+** installed. To check, run:
```bash
python --version
```

---

## Installation & Setup

1️. Clone this repository:
```bash
git clone <your_repository_url>
cd ANALISIS_SENTIMEN_SHOPE
```

2. (Optional but recommended) Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate        # On Windows use: venv\Scripts\activate
```

3. Install the required dependencies:
```bash
pip install -r REQUIREMENTS.txt
```

---

## Running the Project

You can open the notebooks in Jupyter to run the project steps:

```bash
jupyter notebook
```

- To **scrape Shopee reviews**, open:
  ```
  SCRAPING DATA/SCRAPING_A387YBM185.ipynb
  ```
- To **build and evaluate the model**, open:
  ```
  PELATIHAN MODEL/MODEL_A387YBM185.ipynb
  ```

---

## Technologies

- **Python**   
- **Pandas**, **NumPy**  
- **Scikit-learn**   
- **BeautifulSoup**, **Requests**   
- **NLTK / Sastrawi** for Bahasa Indonesia text preprocessing  
- **Jupyter Notebook**   

---

## Goals

- Understand public sentiment towards Shopee through app reviews  
- Apply NLP techniques to clean and prepare real-world text data  
- Train a supervised machine learning model for sentiment classification  
- Evaluate the model's performance using metrics such as accuracy and F1-score

---

