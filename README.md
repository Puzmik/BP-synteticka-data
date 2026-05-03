# Generování syntetických dat pomocí velkých jazykových modelů: Analýza biasu

Repozitář obsahuje materiály k bakalářské práci obhajované na Fakultě informatiky a statistiky Vysoké školy ekonomické v Praze.

**Autor:** Ondřej Pužman  
**Vedoucí práce:** Ing. David Chudán, Ph.D.

## Struktura repozitáře

Každá z testovaných domén má vlastní složku obsahující notebook s analýzou, referenční data, vygenerovaná syntetická data a prompty:

- `arrests/` – Chicago Arrests (kriminalita)
- `car_crashes/` – NYC Motor Vehicle Collisions (dopravní nehody)
- `UCI_heart/` – UCI Heart Disease (klinická data)

Uvnitř každé doménové složky:

- `*.ipynb` – Jupyter notebook s analýzou
- `*.csv` / `*.data` – referenční reálná data
- `zero shot/` – syntetická data ze zero-shot promptu + `prompt.txt` se zněním promptu
- `few shot/` – syntetická data z advanced promptu + `prompt.txt` se zněním promptu
- `*.svg` – výsledné grafy z analýzy (většina použita v práci)
