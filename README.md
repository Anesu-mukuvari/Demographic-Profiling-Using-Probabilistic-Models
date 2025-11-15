# Demographic Profiling of Purchase Intent Using Bayesian Networks

This repo contains a BCom Honours analytics project focused on identifying which demographic combinations predict purchase intent in retail using probabilistic models. Building on Bayesian networks from Assignment 2, we analyze balanced and unbalanced models to uncover customer segmentation insights.

## Project Overview
- **Objective:** Determine most predictive demographic profiles for four purchase intention types by analyzing Bayesian networks.
- **Dataset:** Soweto subsistence retail dataset (public, Data in Brief)
- **Continuation:** Uses Bayesian network models and synthetic data generated in Assignment 2.

## Methodology

1. **Load Bayesian Networks**
   - Utilized original and three balanced Bayesian network models from Assignment 2.
2. **Extract Demographics**
   - Gender, Age, Marital Status, Education, Employment, Customer Type, Shopping Frequency.
3. **Conditional Probability Analysis**
   - Calculated purchase probability for every unique demographic combination.
   - Ranked top profiles for four purchase intention types.
4. **Model Comparison**
   - Evaluated patterns and bias in balanced vs unbalanced models.
   - Interpreted changes in predictive profiles.
5. **Business Insights**
   - Segmentation, targeted marketing strategies, bias analysis.

## Key Results
- Balanced Bayesian models identified hidden customer segments and predictive demographics missed by original data.
- Shopping frequency, age, and education were top predictors.
- Trade-off between prediction accuracy and demographic representation.

## Technical Stack
- Python, pgmpy, pandas, scikit-learn, data visualization

## Files Included
- Colab notebook (.py): Full probabilistic analysis
- Presentation slides: Project summary and visuals
- Decision tables and inference diagrams

## Skills Demonstrated
- Bayesian inference and probabilistic reasoning
- Customer profiling and segmentation
- Bias analysis and results interpretation
- Retail analytics and data-driven recommendations

## Authors
Philip C., Mukuvari A., Matlhare T.

## License
For academic, educational, and demonstration purposes.
