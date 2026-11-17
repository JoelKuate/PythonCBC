# Formation Python — CBC

Extrait essentiel de la formation Python (Jour 1 et Jour 2), adapté pour CBC.
Dataset et exemples rebaptisés CBC (anciennement Beobank). Formation originale complète non modifiée, dans les dossiers `Jour_1_...` / `Jour_2_...` à la racine du repo.

## Structure

```
CBC/
├── Jour1/
│   ├── Cours_Jour1.ipynb              -> cours formateur, bases Python
│   ├── Exercices_Jour1.ipynb          -> exercices participant (TODO / "votre code")
│   └── Scenario_Exercices_Jour1.ipynb -> mise en situation, blancs à remplir (___)
│
└── Jour2/
    ├── 01_NumPy/
    │   ├── Cours_NumPy.ipynb
    │   ├── Exercices_NumPy.ipynb
    │   └── CTR.csv
    │
    ├── 02_Pandas_Initiation/
    │   ├── Cours_Pandas_Initiation.ipynb
    │   ├── Exercices_Pandas_Initiation.ipynb
    │   └── CTR.csv, TIE.csv, TIE_ADR.csv, TIE_X_CTR.csv
    │
    └── 03_Pandas_Complet/
        ├── Cours_Pandas_Complet.ipynb
        ├── Exercices_Pandas_Complet.ipynb
        └── CTR.csv, TIE.csv, TIE_ADR.csv, TIE_X_CTR.csv
```

## Ordre de parcours

1. `Jour1/Cours_Jour1.ipynb` — cours
2. `Jour1/Exercices_Jour1.ipynb` puis `Scenario_Exercices_Jour1.ipynb` — exercices à trous
3. `Jour2/01_NumPy/Cours_NumPy.ipynb` → `Exercices_NumPy.ipynb`
4. `Jour2/02_Pandas_Initiation/Cours_Pandas_Initiation.ipynb` → `Exercices_Pandas_Initiation.ipynb`
5. `Jour2/03_Pandas_Complet/Cours_Pandas_Complet.ipynb` → `Exercices_Pandas_Complet.ipynb`

## Notes

- Chaque notebook d'exercice contient des blancs à compléter (`TODO`, `# votre code`, `___`) — pas de corrigé dans ce dossier.
- Les CSV (`CTR.csv`, `TIE.csv`, `TIE_ADR.csv`, `TIE_X_CTR.csv`) sont copiés localement dans chaque sous-dossier : chaque notebook s'exécute de façon autonome, chemin relatif `./nom.csv`.
- Toute mention "Beobank" a été remplacée par "CBC" dans ces notebooks.
