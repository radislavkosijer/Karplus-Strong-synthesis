# Karplus-Strong sinteza zvuka

Ovaj projekat implementira Karplus-Strong algoritam za sintezu žičanih instrumenata u Pythonu. Koristi se bijeli šum kao pobudni signal koji se zatim filtrira i vraća kroz kašnjenje kako bi se dobili realistični tonovi.

U projektu se generišu tonovi (npr. A4), cijele muzičke ljestvice (C-dur), kao i akordi i efekti poput pozicije trzalice i overdrive distorzije. Moguće je kontrolisati trajanje tona parametrima `t60` i `S`.

Sav kod je napisan u Pythonu i koristi biblioteke NumPy, SciPy i Matplotlib. Rezultati se mogu vizualizovati i čuti kao `.wav` fajlovi.
