# Bike Sharing Data Analysis Dashboard

Dashboard ini merupakan bagian dari proyek analisis data untuk melihat pola peminjaman sepeda berdasarkan dataset `hour.csv`. Dashboard dibuat dengan Streamlit agar dapat menampilkan hasil analisis secara interaktif dan mudah dipahami.

---

## Struktur Proyek

submission/
├── dashboard/
│ └── dashboard.py 
├── data/
│ └── hour.csv 
├── notebook.ipynb 
├── requirements.txt 
├── README.md 
└── url.txt 


---

## Setup Environment - Anaconda

```
bash
conda create --name bike-sharing-dash python=3.9
conda activate bike-sharing-dash
pip install -r requirements.txt
```

## Setup Environment - Shell/Terminal
```
mkdir bike-sharing-dashboard
cd bike-sharing-dashboard
python -m venv venv
venv\Scripts\activate     
pip install -r requirements.txt
```
## Run Streamlit App
streamlit run dashboard.py
