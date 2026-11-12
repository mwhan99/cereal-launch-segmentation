# Data

| File | Source | In this repo? |
|---|---|---|
| `cereal_nutrition.xlsx` | *80 Cereals* dataset: nutrition facts for 77 US breakfast cereals, publicly available on Kaggle | Yes |
| `consumer_survey.csv` | Cereal attitudes survey, provided by the instructor for NYU MASY 1215 (Data-Driven Decision Making) | No, course material |
| `survey_questionnaire.docx` | Questionnaire for the survey above, from the same course | No, course material |

## The consumer survey

800 respondents, 29 columns:

- `CustomerID`
- **8 demographic questions:** `Age`, `Gender`, `Income`, `Marital_Status`, `Children_at_Home`, `Primary_Shopper`, `Work_Arrangement`, `Dietary_Restriction`
- **20 attitude statements:** `Q1`–`Q20`, each rated 1 (strongly disagree) to 5 (strongly agree). The wording of each statement is listed in the `QUESTIONS` dictionary in `analysis.ipynb`.

To re-run Part 2 of the notebook, place a file with this layout at `data/consumer_survey.csv`.
