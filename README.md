# Women's Health and Financial Stability in India

This repository contains the research paper and code for the study titled **"Women's Health and Financial Stability in India"**, conducted as part of the Econometrics II coursework at FLAME University. The study investigates how financial stability influences long-term health outcomes among rural Indian women, using nationally representative survey data and applied econometric techniques.

## Research Objective

The study examines whether financial stability—measured through bank account ownership, capital assets, and savings group participation—is associated with a reduced likelihood of chronic morbidities in women. It also evaluates how health insurance coverage and decision-making autonomy affect health, while controlling for demographic factors.

### Morbidities Considered

The dependent variable represents whether a woman is affected by any of the following long-term health conditions:

- Hypertension (High Blood Pressure)
- Diabetes
- Tuberculosis
- Heart Disease
- Cancer
- Asthma
- Leprosy
- Cataract
- Epilepsy
- Paralysis
- Polio

## Data Source

- **India Human Development Survey-II (IHDS-II), 2011–12**
  - Conducted by the National Council of Applied Economic Research (NCAER) and the University of Maryland
  - Nationally representative sample of over 42,000 households
  - Data includes household, individual, and eligible women modules

## Methodology

- **Dependent Variable**: Presence of one or more long-term morbidities (binary)
- **Main Independent Variable**: Ownership of a bank account
- **Control Variables**: Education, age, caste, meals per day, marital status, health insurance type (public/private), decision-making autonomy, asset ownership, group savings participation

### Econometric Models

- Linear Probability Model (LPM) for baseline estimates
- Logit Model for final estimation
- Marginal effects and odds ratios reported to interpret coefficients

### Diagnostics

- Breusch-Pagan test for heteroskedasticity
- Variance Inflation Factor (VIF) for multicollinearity
- Ramsey RESET test for omitted variable bias

## Tools and Technologies

- **R**: Data wrangling, statistical modeling, marginal effect calculation, and visualization
- **Stata**: Econometric diagnostics and robustness checks
- **LaTeX**: Academic paper formatting
- **Git/GitHub**: Version control and open research access

## Key Findings

- Women who own a bank account are marginally less likely to report long-term morbidities, although the effect is statistically weak in the logit model.
- Greater financial security through asset ownership and savings group membership is associated with lower morbidity.
- Private health insurance is significantly associated with improved health outcomes.
- Unexpected findings:
  - A positive association between education and morbidity, potentially due to increased awareness/reporting
  - Lower morbidity among disadvantaged caste groups, possibly reflecting reporting or access bias

## Policy Implications

- Financial inclusion initiatives must be accompanied by literacy and accessibility to be effective.
- Private insurance appears more protective than public schemes; improved implementation of government coverage is needed.
- Promoting capital ownership and group savings participation can serve as scalable strategies to improve women’s health.

