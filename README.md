# MSProteomics Shiny App

Interaktivní **Shiny aplikace pro analýzu LC-MS/MS proteomických dat** (intenzity na úrovni proteinů) se zaměřením na běžný workflow:
- kontrola a předzpracování dat (intenzity, popisné sloupce)
- práce s **missing values** (vizualizace/diagnostika)
- **diferenciální analýza** mezi skupinami (typicky **limma** a **DEqMS**)
- navazující interpretace výsledků (např. enrichment analýzy – GO/KEGG/Reactome – pokud je v projektu zapnuté)
-integrovaný Volcano plotter

Aplikace je určená pro rychlou exploraci dat, tvorbu přehledných tabulek a grafů a export výsledků do CSV pro další použití.

---

## Co je v repozitáři

- **`Pruchod aplikací krok za krokem.pdf`**  
  Uživatelský manuál (krok za krokem), který popisuje ovládání aplikace a typický postup analýzy.

- **`MS25289184_ttest.xlsx`**  
  **Testovací soubor** pro vyzkoušení načtení dat a práce s aplikací.

- **`MSProteomicsPortable.zip`**   
  Přenosná/balíčkovaná verze aplikace .

---

## Spuštění aplikace

Rozbalit zip a v hlavním adresáři spustit Launch_App.bat


## Vstupní data

Aplikace očekává tabulku s intenzitami (proteiny × vzorky) a základními popisnými sloupci (např. identifikátory proteinů, geny, popis proteinu, počet peptidů apod.).  
Vstupní soubor by měl vypadat jako  **`MS25289184_ttest.xlsx`**.

---

## Kontakt / autor

Pokud je potřeba něco doplnit nebo upravit, kontaktujte autora repozitáře (viz GitHub profil).
