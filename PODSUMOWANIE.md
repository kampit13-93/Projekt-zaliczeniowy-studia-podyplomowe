## Podsumowanie

Po przeprowadzeniu działań związanych ze wstępnym przetwarzaniem i czyszczeniem danych ustalono rozkład klas, liczbę instancji oraz liczbę cech. Występują dwie klasy: **grzyby jadalne** oraz **grzyby trujące**. Zbiór danych zawiera **23 cechy łącznie z kategorią**, więc do zbioru danych treningowych wejdzie maksymalnie **22 cechy**. Liczba instancji wynosi **8124**.

**Liczność klas:**

- Grzyby jadalne: 51.8% (4208)
- Grzyby trujące: 48.2% (3916)

Z przeprowadzonej wizualizacji danych wynika, że **możliwe jest jednoznaczne określenie klasy** na podstawie pewnych wartości cech.

### Wyniki klasyfikatorów

Wyniki uzyskano dla oryginalnego zbioru danych oraz jego wersji **standaryzowanej** i **normalizowanej**:

- **Regresja logistyczna**:
  - Krzywe ROC pokazują niemal perfekcyjne działanie klasyfikatora.
  - Krzywe uczenia zbiegają się na końcach.

- **KNN (k najbliższych sąsiadów)**:
  - Skuteczność klasyfikatora jest **perfekcyjna**, niezależnie od przygotowania danych.

- **SVM (maszyna wektorów nośnych)**:
  - Wersje **liniowa** i **wielomianowa** osiągają bardzo wysoką jakość.
  - **Wersja sigmoidalna** działa najgorzej – klasyfikuje błędnie **8 grzybów trujących jako jadalne**.
  - W wersji standaryzowanej krzywe uczenia zbiegają się najmniej ze wszystkich.

- **Naiwny klasyfikator Bayesa**:
  - Nie popełnia niebezpiecznych błędów.
  - **33 grzyby jadalne** są błędnie sklasyfikowane jako trujące.

- **Drzewa decyzyjne i lasy losowe**:
  - Nie popełniają żadnych błędów.
  - Krzywe uczenia **ładnie zbiegają się ze sobą**
