Prognozowanie ceny złota (XAUPLN)
Autor: Jan Zdaniewicz
Środowisko: Jupyter Notebook
Język: Python

📌 Cel projektu
Celem projektu jest stworzenie modelu predykcyjnego do prognozowania dziennej ceny złota (XAUPLN) na podstawie danych historycznych i wybranych zmiennych makroekonomicznych oraz rynkowych.

🧩 Wykorzystane dane
W analizie uwzględniono dane dzienne z okresu 19.07.2010 – 12.06.2025 dla następujących instrumentów finansowych:

Symbol	Opis
XAUPLN	Złoto / PLN (zmienna celu)
XAGPLN	Srebro / PLN
XPTPLN	Platyna / PLN
BTCPLN	Bitcoin / PLN
USDPLN	Dolar amerykański / PLN

Źródło danych: Stooq.pl

⚙️ Metodologia
Wczytanie danych z plików CSV

Filtrowanie danych do wspólnego zakresu czasowego

Łączenie danych po dacie

Eksploracyjna analiza danych (EDA)

Modelowanie regresyjne:

Regresja liniowa (sklearn)

Model sieci neuronowej (Keras / TensorFlow)

Ocena modelu przy pomocy metryk:

MAE, MSE, RMSE, R²

🧠 Technologie i biblioteki
pandas, numpy

matplotlib, seaborn

scikit-learn

tensorflow.keras

📈 Wyniki
Projekt zakłada porównanie efektywności modeli na podstawie ich dokładności predykcji oraz identyfikację zmiennych mających największy wpływ na zmienność ceny złota.

🗂 Struktura katalogów
Kopiuj
Edytuj
Projekt/
├── Data/
│   ├── xaupln_d.csv
│   ├── xagpln_d.csv
│   └── ...
├── Jan_Zdaniewicz_190023.ipynb
└── README.md
✅ Wymagania
Python 3.8+

Środowisko Jupyter

Pakiety wskazane w sekcji „Technologie”

📬 Kontakt
W razie pytań lub sugestii, proszę o kontakt przez GitHub lub e-mail.