# 🎯 Friend Seeker

**Friend Seeker** 🚀 to aplikacja stworzona w **Streamlit**, która
pomaga znaleźć osoby o podobnych zainteresowaniach 👥. Na podstawie
krótkiej ankiety dopasowuje Cię do odpowiedniej grupy i pokazuje jej
charakterystykę.

------------------------------------------------------------------------

## 🛠️ Technologie

-   🐍 **Python**\
-   📊 **Streamlit** -- interfejs webowy\
-   🤖 **PyCaret** -- model uczenia maszynowego (klasteryzacja)\
-   📈 **Plotly Express** -- interaktywne wykresy\
-   📄 **Pandas** -- przetwarzanie danych

------------------------------------------------------------------------

## 🔍 Jak to działa?

1.  📝 **Wypełniasz krótką ankietę** w panelu bocznym (wiek,
    wykształcenie, ulubione miejsca, zwierzęta, płeć).\
2.  🤖 **Model ML** przewiduje, do którego klastra (grupy) należysz.\
3.  📊 **Otrzymujesz opis swojej grupy** + interaktywne wykresy
    pokazujące jej skład.\
4.  🔄 **Możesz też przejrzeć inne grupy** i zobaczyć ich
    charakterystykę.

------------------------------------------------------------------------

## 📊 Przykładowe wizualizacje

-   👶👩👴 Rozkład wieku w grupie\
-   🎓 Poziom wykształcenia\
-   🐶🐱 Ulubione zwierzęta\
-   🌲🏞️🏖️ Ulubione miejsca\
-   🚹🚺 Rozkład płci

------------------------------------------------------------------------

## 🚀 Uruchomienie

1.  Zainstaluj wymagane biblioteki:

    ``` bash
    pip install -r requirements.txt
    ```

2.  Uruchom aplikację:

    ``` bash
    streamlit run app.py
    ```

3.  Otwórz w przeglądarce adres 👉 <http://localhost:8501>

------------------------------------------------------------------------

## 📂 Struktura projektu

    .
    ├── app.py                                # Kod aplikacji Streamlit
    ├── welcome_survey_simple_v2.csv          # Dane wejściowe
    ├── welcome_survey_clustering_pipeline_v2 # Wytrenowany model ML
    ├── welcome_survey_cluster_names_and_descriptions_v2.json # Opisy klastrów
    └── README.md                             # Dokumentacja

------------------------------------------------------------------------

## 🎉 Funkcje aplikacji

-   ✅ Dopasowanie do grupy na podstawie krótkiego formularza\
-   ✅ Wyświetlenie opisu grupy i jej charakterystyki\
-   ✅ Interaktywne wykresy 📊\
-   ✅ Możliwość porównania różnych grup

------------------------------------------------------------------------

💡 **Friend Seeker** pomaga odkryć, do której społeczności pasujesz
najbardziej i znaleźć osoby o podobnych zainteresowaniach!
