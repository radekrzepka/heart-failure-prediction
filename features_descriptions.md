## Dataset description (in Polish)

1. **Wiek (Age)**

   - **Typ**: Liczbowy (lata)
   - **Znaczenie**: Wiek pacjenta w latach.

2. **Płeć (Sex)**

   - **Typ**: Binarny (0, 1)
   - **Znaczenie**: Płeć biologiczna pacjenta. `0` = kobieta, `1` = mężczyzna.

3. **Typ bólu w klatce piersiowej (Chest Pain Type, cp)**

   - **Typ**: Kategoryczny (4 wartości)
   - **Znaczenie**: Określa rodzaj bólu w klatce piersiowej:
     - 0: Typowa dławica piersiowa (angina)
     - 1: Nietypowa dławica piersiowa
     - 2: Ból niedławicowy
     - 3: Bezobjawowy

4. **Ciśnienie tętnicze spoczynkowe (Resting Blood Pressure, trestbps)**

   - **Typ**: Liczbowy (mm Hg)
   - **Znaczenie**: Ciśnienie tętnicze mierzone w spoczynku (podczas wizyty lekarskiej), w milimetrach słupa rtęci (mm Hg).

5. **Poziom cholesterolu w surowicy (Serum Cholesterol, chol)**

   - **Typ**: Liczbowy (mg/dl)
   - **Znaczenie**: Poziom cholesterolu w surowicy, w miligramach na decylitr.

6. **Cukier we krwi na czczo (Fasting Blood Sugar, fbs)**

   - **Typ**: Binarny (0, 1)
   - **Znaczenie**: Informuje, czy poziom cukru we krwi na czczo jest > 120 mg/dl.
     - 0: FBS ≤ 120 mg/dl
     - 1: FBS > 120 mg/dl

7. **Wyniki elektrokardiograficzne w spoczynku (Resting ECG, restecg)**

   - **Typ**: Kategoryczny (wartości 0, 1, 2)
   - **Znaczenie**: Wynik EKG w spoczynku:
     - 0: Prawidłowy
     - 1: Nieprawidłowości załamków ST-T (np. odwrócenie załamka T, uniesienie lub obniżenie odcinka ST > 0,05 mV)
     - 2: Prawdopodobne lub pewne przerosty lewej komory serca

8. **Maksymalna osiągnięta częstość akcji serca (Maximum Heart Rate Achieved, thalach)**

   - **Typ**: Liczbowy (uderzenia na minutę)
   - **Znaczenie**: Najwyższa częstość akcji serca (tętno) osiągnięta podczas wysiłku lub testu wysiłkowego.

9. **Dławica wywołana wysiłkiem (Exercise Induced Angina, exang)**

   - **Typ**: Binarny (0, 1)
   - **Znaczenie**: Określa, czy u pacjenta występuje dławica podczas wysiłku:
     - 0: Brak dławicy przy wysiłku
     - 1: Dławica wywołana wysiłkiem

10. **Oldpeak**

    - **Typ**: Liczbowy (depresja odcinka ST)
    - **Znaczenie**: Depresja odcinka ST wywołana wysiłkiem w porównaniu do stanu spoczynkowego (w milimetrach). Wskazuje możliwe niedokrwienie mięśnia sercowego.

11. **Nachylenie odcinka ST podczas wysiłku (Slope of the Peak Exercise ST Segment, slope)**

    - **Typ**: Kategoryczny (wartości 0, 1, 2)
    - **Znaczenie**: Określa kształt (nachylenie) odcinka ST podczas szczytowego wysiłku:
      - 0: Wznoszący
      - 1: Płaski
      - 2: Opadający

12. **Liczba głównych naczyń (ca)**

    - **Typ**: Liczbowy (wartości całkowite 0–3)
    - **Znaczenie**: Liczba głównych naczyń (0–3) widocznych w obrazowaniu metodą fluoroskopii. Większa liczba może wskazywać bardziej zaawansowaną chorobę serca.

13. **Thal**
    - **Typ**: Kategoryczny (0, 1, 2)
    - **Znaczenie**: Wynik testu obciążeniowego z użyciem talu:
      - 0: Prawidłowy
      - 1: Defekt utrwalony (defekt obecny stale)
      - 2: Defekt odwracalny (pojawiający się podczas wysiłku, zanikający w spoczynku)

**Zmienna docelowa (Target)**

- **Typ**: Binarny (0 lub 1)
- **Znaczenie**: Informuje o obecności choroby serca.
  - 0: Brak choroby serca
  - 1: Obecność choroby serca
