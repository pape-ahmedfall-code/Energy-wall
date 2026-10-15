# Energy Wall — L'IA face au mur énergétique

Projet de Master 2 IA. Analyse prospective de la consommation d'énergie, des émissions et de l'eau liées à l'IA, avec trois scénarios chiffrés (2027, 2030, 2035) et trois recommandations pour un décideur public.

> Statut : en construction. Rendu prévu le 2 novembre 2026.

## 1. Contexte et question posée

*(À rédiger — phase 1)* Décembre 2029 : une coupure d'électricité paralyse un train. L'IA en est-elle responsable ? Peut-elle aider ? Quel est le coût pour la planète ? Ce projet répond à ces questions à l'aide d'une veille sourcée et d'un modèle de projection.

## 2. Les 3 métriques clés

| Métrique | Unité | Pourquoi |
| --- | --- | --- |
| Consommation d'électricité | TWh/an | Mesure le « mur » énergétique |
| Émissions de gaz à effet de serre | MtCO2e/an | Mesure l'impact climatique (GHG Protocol) |
| Consommation d'eau | millions de m3/an | Mesure l'impact sur les ressources |

## 3. Périmètre

- Trajectoire et obstacles : monde.
- Recommandations : France et Europe.
- Années : base 2024 ; projections 2027, 2030, 2035.

## 4. Veille scientifique, technologique et réglementaire

### 4.1 Trajectoire : comment en est-on arrivé là ?
*(À compléter)*

### 4.2 Obstacles : quels verrous restent à franchir ?
*(À compléter)*

### 4.3 Innovations : qu'est-ce qui peut aider ?
*(À compléter)*

### 4.4 Impact environnemental
*(À compléter)*

### 4.5 Cadre réglementaire
*(À compléter : directive efficacité énergétique, AI Act, CSRD)*

### 4.6 Bibliographie
*(Une entrée par source, au format : Auteur, titre, organisme, année, [lien]. Voir `data/sources.csv` et `docs/fiches_veille/`.)*

## 5. Méthode de modélisation

*(À rédiger — phase 2)* Chaîne : scaling laws → compute (entraînement et inférence) → énergie (efficacité matérielle, utilisation, PUE) → CO2e (intensité du réseau) → eau (WUE).

## 6. Scénarios

*(À rédiger — phase 3)* Pessimiste, normal, optimiste : paramètres, résultats, incertitudes.

## 7. Recommandations

*(À rédiger — phase 3)* Trois recommandations actionnables, fiables et stratégiques.

## 8. Reproduire les résultats

```bash
git clone https://github.com/<votre-compte>/Energy-wall.git
cd Energy-wall
python -m venv .venv
source .venv/bin/activate        # Windows : .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook notebooks/energy_wall.ipynb
```

Dans le notebook : *Kernel → Restart & Run All*.

## 9. Structure du dépôt

```
Energy-wall/
├── README.md                  veille, méthode, résultats
├── requirements.txt           dépendances Python
├── data/
│   ├── sources.csv            tous les chiffres sourcés (valeur, unité, année, source)
│   ├── raw/                   données brutes téléchargées
│   └── processed/             données nettoyées
├── notebooks/
│   └── energy_wall.ipynb
├── figures/                   graphiques exportés
├── docs/fiches_veille/        fiches de lecture par source
└── presentation/              présentation finale (PPTX et PDF)
```

## 10. Auteur

Ahmed Ndery — Master 2 IA. Licence MIT.
