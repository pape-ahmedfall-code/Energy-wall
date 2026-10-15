# Energy Wall — AI and the Energy Wall

Master 2 AI project. A forward-looking analysis of the electricity, greenhouse-gas and water footprint of AI, with three quantified scenarios (2027, 2030, 2035) and three recommendations for a public decision-maker.

> Status: work in progress. Submission due on 2 November 2026.

## 1. Context and research question

*(To be written — phase 1)* December 2029: a power outage stops a train. Is AI responsible? Can it help? What does it cost the planet? This project answers these questions with a sourced technology watch and a projection model.

## 2. The 3 key metrics

| Metric | Unit | Why it matters |
| --- | --- | --- |
| Electricity consumption | TWh/year | Measures the "energy wall" |
| Greenhouse-gas emissions | MtCO2e/year | Measures climate impact (GHG Protocol) |
| Water consumption | million m³/year | Measures pressure on natural resources |

## 3. Scope

- Trajectory and obstacles: world.
- Recommendations: France and Europe.
- Years: baseline 2024; projections for 2027, 2030 and 2035.

## 4. Scientific, technological and regulatory watch

### 4.1 Trajectory: how did we get here?
*(To be completed)*

### 4.2 Obstacles: which bottlenecks remain?
*(To be completed)*

### 4.3 Innovations: what can help?
*(To be completed)*

### 4.4 Environmental impact
*(To be completed)*

### 4.5 Regulatory framework
*(To be completed: Energy Efficiency Directive, AI Act, CSRD)*

### 4.6 Bibliography
*(One entry per source, formatted as: Author, title, organisation, year, [link]. See `data/sources.csv` and `docs/fiches_veille/`.)*

## 5. Modelling method

*(To be written — phase 2)* Calculation chain: scaling laws → compute (training and inference) → energy (hardware efficiency, utilisation, PUE) → CO2e (grid carbon intensity) → water (WUE).

## 6. Scenarios

*(To be written — phase 3)* Pessimistic, baseline, optimistic: parameters, results, uncertainty.

## 7. Recommendations

*(To be written — phase 3)* Three recommendations that are actionable, reliable and strategic.

## 8. Reproducing the results

```bash
git clone https://github.com/pape-ahmedfall-code/Energy-wall.git
cd Energy-wall
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook notebooks/energy_wall.ipynb
```

In the notebook: *Kernel → Restart & Run All*.

## 9. Repository structure

```
Energy-wall/
├── README.md                  watch, method, results
├── requirements.txt           Python dependencies
├── data/
│   ├── sources.csv            every sourced figure (value, unit, year, source)
│   ├── raw/                   downloaded raw data
│   └── processed/             cleaned data
├── notebooks/
│   └── energy_wall.ipynb
├── figures/                   exported charts
├── docs/fiches_veille/        reading notes, one per source
└── presentation/              final presentation (PPTX and PDF)
```

## 10. Author

Pape Ahmed FALL — Master 2 AI. MIT licence.
