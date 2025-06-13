# 📊 Prognozowanie ceny złota (XAUPLN)

**Autor:** Jan Zdaniewicz  
**Środowisko:** Jupyter Notebook  
**Język:** Python

## 🎯 Cel projektu

Celem projektu jest stworzenie modelu predykcyjnego do prognozowania dziennej ceny złota (**XAUPLN**) na podstawie danych historycznych oraz wybranych zmiennych makroekonomicznych i rynkowych.

## 📁 Wykorzystane dane

W analizie wykorzystano dzienne dane z okresu **19.07.2010 – 12.06.2025** dla następujących instrumentów:

| Symbol   | Opis                             |
|----------|----------------------------------|
| XAUPLN   | Złoto / PLN *(zmienna celu)*     |
| XAGPLN   | Srebro / PLN                     |
| XPTPLN   | Platyna / PLN                    |
| BTCPLN   | Bitcoin / PLN                    |
| USDPLN   | Dolar amerykański / PLN          |

📌 Źródło danych: [Stooq.pl](https://stooq.pl)

## ⚙️ Metodologia

- 📥 Wczytanie danych z plików CSV  
- 🗃 Filtrowanie danych do wspólnego zakresu czasowego  
- 🔗 Łączenie danych po dacie  
- 📊 Eksploracyjna analiza danych (EDA)  
- 🧠 Modelowanie regresyjne:
  - Regresja liniowa (`scikit-learn`)
  - Sieć neuronowa (`Keras` / `TensorFlow`)
- 🧾 Ocena modeli przy pomocy metryk:
  - MAE, MSE, RMSE, R²

## 🧪 Technologie i biblioteki

- `pandas`, `numpy`  
- `matplotlib`, `seaborn`  
- `scikit-learn`  
- `tensorflow.keras`

## 📂 Struktura projektu

- **Projekt/**
  - **Data/**
    - `xaupln_d.csv`
    - `xagpln_d.csv`
    - *(inne pliki danych)*
  - `Jan_Zdaniewicz_190023.ipynb`
  - `README.md`

## ✅ Wymagania środowiskowe

- Python 3.8+
- Jupyter Notebook
- Biblioteki: jak wyżej

## 📬 Kontakt

Masz pytania? Skontaktuj się przez GitHub lub mailowo.
