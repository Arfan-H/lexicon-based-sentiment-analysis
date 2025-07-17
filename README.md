# lexicon-based-sentiment-analysis
# Lexicon-Based Sentiment Analysis on Tweets about Capres (Bahasa Indonesia)

Proyek ini melakukan analisis sentimen berbasis _lexicon_ terhadap tweet berbahasa Indonesia yang membahas calon presiden (capres). Pendekatan ini mengkategorikan teks ke dalam sentimen **positif**, **negatif**, atau **netral** menggunakan kamus sentimen sederhana.

## ✨ Fitur Utama

- Scraping tweet dari Twitter menggunakan kata kunci terkait capres
- Preprocessing teks (case folding, tokenizing, stopword removal, stemming)
- Klasifikasi sentimen berbasis lexicon (kamus kata berlabel sentimen)
- Visualisasi hasil sentimen dalam bentuk pie chart
- Mendukung teks Bahasa Indonesia

## 🔍 Sumber Data

Data dikumpulkan melalui **scraping Twitter** menggunakan kata kunci yang berkaitan dengan capres, seperti:
- `"Prabowo"`, `"Ganjar"`, `"Anies"`
- `"Capres 2024"`, `"Debat Capres"`, dll.

> Catatan: Pengumpulan data dilakukan menggunakan API/SNScrape sesuai kebijakan penggunaan publik.

## 🧪 Teknologi yang Digunakan

- Python
- Jupyter Notebook
- NLTK & Sastrawi untuk preprocessing
- Matplotlib untuk visualisasi
- SNScrape / Tweepy (untuk scraping data Twitter)


