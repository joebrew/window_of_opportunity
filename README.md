# window_of_opportunity
Window of Opportunity (PATH project in Southern Mozambique)

## Details
- CISM was doing a KAP survey in the Boane community to find out what mothers know.
- Now a consultant is carrying out the rest of the protocol.

## Components
- MCH
- Nutrition
- Early child development

## Objectivos
- Descrever perfil demografico das maes que usam servicos de saude
- Descrever KAP
- Identificar barriers and facilitators to K, A, and P

## Status
- Survey was 200 households (should have been 300 +, but funding short)
- Data were collected from 9 health facilities (births, admissions, maternal deaths, vaccination coverage, in/outpatient consultations, etc.)
- Data already collected
- Descriptive analysis already done
- Due to small sample size, most analyses were univariate
- Data was cleaned with Barcelona people
- Khatia developed an analytical plan
  - Includes lots of dummy tables (Khatia can provide this)

# Problems
- Need to create SES status
  - The idea is to combine a pre-defined list of SES variables into one or more SES indices, using PCA
- See where houses stand
- Examine extent to which certain outcomes (below) are predicted by SES
  - Outcomes (several per outcome "group"):
    - Birth (1)
      - Age at firstr birth (48)
      - Reported number of ANC visits (50)
      - REported care seeking practice sfor pregnancy complications (59)
      - Place of past or upcoming birth (63)
      - How long after delivery must a woman attend the post-partum visit? (87)
      - Type of food eaten during pregnancy (95, 96, 97)
    - Child health care (group 2)
      - A
      - B
      - C
    - Feeding practices (group 3)
      - A
      - B
    - Early child development (group 4)
      - A
      - B

# Process
Two steps:
  1. Create simple model (6 models actually) for how SES predicts our outcomes
  2. Add the other predictors to the model (Head of household education, caretakers education, distance to HF, respondents age)
