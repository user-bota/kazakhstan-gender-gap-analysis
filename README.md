# Kazakhstan Gender Gap Analysis

An interactive Tableau dashboard analyzing Kazakhstan's gender gap trends using the World Economic Forum's Global Gender Gap Index (2005–2023).

**View the interactive dashboard on Tableau Public:**  
https://public.tableau.com/app/profile/akbota.serikkyzy/viz/KazakhstanGenderGapAnalysis/KazakhstanGenderGapAnalysis?publish=yes

## Dashboard Preview

![Kazakhstan Gender Gap Analysis](Kazakhstan%20Gender%20Gap%20Analysis.png)

## Key Findings

- Kazakhstan closes **71%** of its overall gender gap, ranking near the global median.
- **Educational Attainment** has reached near-perfect parity (**1.000**) since 2005.
- **Health & Survival** sits at **0.98**, near parity.
- **Economic Opportunity** is at **0.75** and slowly improving.
- **Political Empowerment** lags dramatically at just **0.12** about a sixth of the Economic Opportunity score, and the primary driver of the country's overall gap.
- The overall index has plateaued around **0.72** since 2011, with almost no measurable progress in over a decade.
- Kazakhstan leads all of Central Asia (ahead of Kyrgyzstan, Tajikistan, and Uzbekistan), suggesting the gap reflects a broader post-Soviet regional pattern rather than a Kazakhstan-specific issue.

## Why This Gap Exists

Soviet-era policy pushed mass female education starting in the 1920s, and Kazakhstan sustained that investment after independence. Political access, however, never followed the same trajectory, and th[...]

## Data

Source: World Economic Forum Global Gender Gap Index, 2005–2023.

```text
data/
├── raw/
│   ├── gggi_eas.csv     # Economic opportunity sub-index
│   ├── gggi_ggi.csv     # Overall Global Gender Gap Index
│   ├── gggi_hss.csv     # Health & Survival sub-index
│   ├── gggi_pes.csv     # Political Empowerment sub-index
│   └── gggi_pos.csv     # Educational Attainment sub-index
└── merged/
    └── gggi_merged.csv  # Combined dataset used for the dashboard
```

## Tools

- **Tableau** — dashboard design and visualization
- **Python (pandas)** — data merging

## Author

Akbota Serikkyzy — Tableau Public profile
