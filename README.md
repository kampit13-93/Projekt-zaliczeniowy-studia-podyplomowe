# Projekt-zaliczeniowy-studia-podyplomowe-DS

Projekt analizy danych z zastosowaniem algorytmów ML (Python, Kaggle)

## Klasyfikacja Grzybów – Projekt Zaliczeniowy

Projekt polega na klasyfikacji grzybów jako **jadalne** lub **trujące** na podstawie danych opisowych.

---

## Zawartość repozytorium

- `Projekt_końcowy_Kamil_Pitner_2025.ipynb` – główny notebook z kodem i analizą
- `PODSUMOWANIE.md` – podsumowanie wyników i wniosków
- `README.md` – opis projektu
- `LICENSE.txt` – licencja
- `REQUIREMENTS.txt` – opis bibliotek

---

## Dane

- Liczba instancji: **8124**
- Liczba cech: **22**
- Klasy: jadalne (51.8%) vs trujące (48.2%)

Źródło danych: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/73/mushroom)

---

## Użyte algorytmy

1. Regresja logistyczna
2. KNN (k najbliższych sąsiadów)
3. SVM – wersje liniowa, wielomianowa, sigmoidalna
4. Naiwny klasyfikator Bayesa
5. Drzewa decyzyjne
6. Las losowy

---

## Wyniki

- **KNN** i **las losowy** osiągnęły perfekcyjną skuteczność.
- **SVM (sigmoidalna)** popełniał błędy klasyfikując grzyby trujące jako jadalne.
- **Regresja logistyczna** i **SVM (liniowy)** radziły sobie bardzo dobrze.
- Więcej szczegółów w pliku `PODSUMOWANIE.md`.

---

## Wymagania

Projekt działa w środowisku Jupyter Notebook.  
Zalecane biblioteki (można zainstalować przez pip):  
`pip install pandas numpy matplotlib seaborn scikit-learn`

---

## Licencja

Kod źródłowy zawarty w tym repozytorium został stworzony przeze mnie i udostępniony na licencji MIT (patrz plik `LICENSE.txt`).

---

## Licencja danych:

Dane pochodzą z platformy Kaggle, zestaw danych Mushroom Classification jest dostępny na licencji [Kaggle License](https://www.kaggle.com/datasets/uciml/mushroom-classification)

---
