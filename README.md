# Kreator Ścieżki Kariery IT

Aplikacja wspomagająca wybór ścieżki kariery w IT poprzez dopasowanie książek z oferty wydawnictwa Helion do wymaganych umiejętności w danym zawodzie.

## Funkcjonalności

- Wyszukiwanie książek po wybranej ścieżce kariery/zawodzie

![screen1](https://github.com/user-attachments/assets/72e9ed9c-31f1-46f4-b9c7-9df65cfd8699)

![screen2](https://github.com/user-attachments/assets/8fccb065-d028-4619-b3cd-e04c92361791)

- Wyszukiwanie ścieżek kariery na podstawie wybranej książki

![screen3](https://github.com/user-attachments/assets/97619806-74b7-4a1f-9a38-a11e660aceb7)

![screen4](https://github.com/user-attachments/assets/e3232900-e24f-49f3-8c98-d9f2b20cc09c)

- Analiza trendów popularności technologii (Google Trends)
- Raporty branżowe w NotebookLM
- Filtrowanie wyników po:
  - Formacie książek (Ebook, Druk, Audiobook)
  - Dacie wydania
- Eksport wyników do CSV
- Wizualizacja dostępności książek dla wymaganych umiejętności
- Edycja danych źródłowych

## Technologie

- Python 3.9
- Streamlit
- Pandas
- Plotly
- PyTrends
- OpenPyXL

## Struktura projektu

```
career-path-app/
├── app.py              # Główny plik aplikacji
├── requirements.txt    # Lista wymaganych pakietów
├── .streamlit/        # Konfiguracja Streamlit
│   └── config.toml
└── data/              # Pliki z danymi
    ├── lista_ksiazek_pl_HELION_all_formats-2.xlsx
    └── Rozszerzona_lista_zawodow_i_technologii_z_jezykami_programowania-UPDATED2.xlsx
```

## Autor

[Robson2k7](https://github.com/Robson2k7)

## Licencja

Copyright (c) 2024 Robson2k7. Wszelkie prawa zastrzeżone.

Ten projekt jest własnością prywatną. Kod źródłowy i dokumentacja są udostępnione wyłącznie do wglądu.
Zabronione jest:
- Kopiowanie i rozpowszechnianie kodu
- Modyfikowanie kodu
- Komercyjne wykorzystanie
- Używanie kodu lub jego części w innych projektach bez pisemnej zgody autora.

---------------------------------------------------------------------------------------------------------------

# IT Career Path Creator

An application that supports selecting an IT career path by matching books from the Helion publishing house's catalog to the skills required for a given profession.

## Features

- Search for books by selected career path/profession

![screen1](https://github.com/user-attachments/assets/72e9ed9c-31f1-46f4-b9c7-9df65cfd8699)

![screen2](https://github.com/user-attachments/assets/8fccb065-d028-4619-b3cd-e04c92361791)

- Search for career paths based on a selected book

![screen3](https://github.com/user-attachments/assets/97619806-74b7-4a1f-9a38-a11e660aceb7)

![screen4](https://github.com/user-attachments/assets/e3232900-e24f-49f3-8c98-d9f2b20cc09c)

- Analyze technology popularity trends (Google Trends)
- It reports in NotebookLM
- Filter results by:
  - Book format (Ebook, Print, Audiobook)
  - Publication date
- Export results to CSV
- Visualize the availability of books for required skills
- Edit source data

## Technologies

- Python 3.9
- Streamlit
- Pandas
- Plotly
- PyTrends
- OpenPyXL

## Project structure

```
career-path-app/
├── app.py              # Główny plik aplikacji
├── requirements.txt    # Lista wymaganych pakietów
├── .streamlit/        # Konfiguracja Streamlit
│   └── config.toml
└── data/              # Pliki z danymi
    ├── lista_ksiazek_pl_HELION_all_formats-2.xlsx
    └── Rozszerzona_lista_zawodow_i_technologii_z_jezykami_programowania-UPDATED2.xlsx
```

## Author

[Robson2k7](https://github.com/Robson2k7)

## License

Copyright (c) 2024 Robson2k7. All rights reserved.

This project is private property. The source code and documentation are provided for viewing purposes only.
The following actions are prohibited:
- Copying and distributing the code
- Modifying the code
- Commercial use
- Using the code or any part of it in other projects without the written consent of the author.