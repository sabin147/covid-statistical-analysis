# COVID Treatment & Age — Statistical Analysis

**Type:** Academic Mini Project  
**Institution:** Roskilde University  
**Course:** BC4-8: Statistical Models  
**Authors:** Sabin Ghimire, Anne Margaret Lorenzen  
**Year:** 2025

## Research Questions

1. Is there a significant difference in survival rates between hydroxychloroquine and standard treatment?
2. Does age group significantly influence survival outcomes?

## Dataset

12 observations covering all combinations of:
- 2 treatments: hydroxychloroquine, standard
- 3 age groups: <50, 50–69, 70+
- 2 outcomes: alive, dead

## Methods

- Chi-Square Test of Independence
- Contingency Table Analysis
- Simpson's Paradox investigation
- Data visualisation with matplotlib and seaborn

## Key Findings

- **Treatment vs survival:** p = 0.253 — no significant association found
- **Age vs survival:** p = 3.99×10⁻⁷ — age is a strong predictor of survival
- Older patients (70+) show significantly higher mortality regardless of treatment type

## Run It
```bash
pip install pandas matplotlib seaborn scipy tabulate jupyter
jupyter notebook covid-treatment-analysis.ipynb
```

## License

MIT License — Copyright (c) 2025 Sabin Ghimire, Anne Margaret Lorenzen
