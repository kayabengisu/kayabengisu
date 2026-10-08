# Bengisu Kaya

MSc Business Administration student at HU Berlin (exchange semester at WU Vienna), focused on data analytics and marketing analytics.
I work in R, Python and SQL on questions such as who to target, what drives an outcome, and whether a correlation still holds once you check how the data was measured.

## Featured projects

**[eu-ecommerce-co2](https://github.com/kayabengisu/eu-ecommerce-co2)**: Does e-commerce growth drive logistics CO2 in the EU?
- *Method:* 2010–2024 panel of 26 EU countries built from live Eurostat, OECD and EDGAR APIs (R); XGBoost and Random Forest with an ablation test, fixed-effects panel checks, k-means clustering, and a PCA-based "Distortion Index" comparing residence-based and territory-based emissions accounting.
- *Result:* E-commerce explains almost nothing (about 1% of XGBoost importance; dropping it leaves R² at 0.90, while dropping freight volume cuts it to 0.42). The apparent link is mostly an accounting artifact: Poland's transport CO2 grew +350% under residence-based accounting but only +46% under territory-based accounting. This is directly relevant to the EU's new standardised emissions reporting under ISO 14083.

**[bank-marketing-ml](https://github.com/kayabengisu/bank-marketing-ml)**: Which bank customers subscribe to a term deposit after a direct-marketing call?
- *Method:* EDA and classification in Python/scikit-learn on 11,260 contacts with a 12% positive rate, comparing models on AUC, recall and F1 instead of accuracy.
- *Result:* Logistic regression reaches AUC 0.90 and 80% recall, but its strongest feature, call duration, is only known after the call (target leakage). Without it, a realistic pre-call model reaches AUC 0.71. Random Forest's low recall (0.34) turned out to be an artefact of the fixed 0.5 threshold; tuning the threshold with cross-validation lifts it above 0.7. *(Team project; my part: EDA and classification. Leakage and threshold follow-up: my own.)*

**[apples-stp-analysis](https://github.com/kayabengisu/apples-stp-analysis)**: Which fresh-apple buyers in Austria should a brand target, and how should it position itself?
- *Method:* Segmentation, targeting and positioning on a 434-respondent survey in R: standardised k-means, χ² profiling, and PCA positioning maps.
- *Result:* The analysis finds four segments. It selects "Eco-Ethical Elites" (22.5% of the sample) as the target: they rank price as least important and sustainability as most important, and 14.9% of them earn over €5,000/month, compared with 3.0% of Budget Traditionalists. *(Team project; my part: segment profiling and targeting.)*

## Currently building

**market-botu** (private): A Berlin grocery-flyer optimizer that uses decision analysis, conjoint-style preference elicitation and basket optimization.

## Tools

![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-DuckDB%20%C2%B7%20SQLite-4479A1?style=flat-square)
![NoSQL](https://img.shields.io/badge/NoSQL-basics-555555?style=flat-square)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square)

## Methods

| Area | Methods |
|---|---|
| Machine learning | Classification, clustering |
| Econometrics & causal inference | Difference-in-differences, instrumental variables, propensity score matching, regression discontinuity |
| Marketing modelling | Conjoint analysis / multinomial logit, market response models, structural equation modelling |
| Decision support | Decision analysis, experimental design |

## Contact

<!-- NOTE (not rendered): replace the LINKEDIN_URL comment below with a full link,
     e.g. [LinkedIn](https://www.linkedin.com/in/<your-handle>/), then delete this note. -->
LinkedIn <!-- LINKEDIN_URL -->
