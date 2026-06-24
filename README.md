# NBA-Player-Longivety-Prediction-Project-
# Naive Bayes Classification -- NBA Player Longevity Prediction

## Project Overview

This project develops a Gaussian Naive Bayes classifier to predict
whether an NBA player will remain in the league for at least five years
(`target_5yrs`). The analysis focuses on evaluating model performance
and interpreting results from a basketball scouting perspective.

## Dataset

The dataset contains engineered player statistics derived from NBA
rookie performance data. The target variable is:

-   **target_5yrs**
    -   `1` = Player remained in the NBA for five or more years
    -   `0` = Player did not remain in the NBA for five years

## Modeling Approach

The following steps were performed:

1.  Loaded the engineered NBA dataset.
2.  Selected `target_5yrs` as the classification target.
3.  Split the data into training and testing sets.
4.  Trained a Gaussian Naive Bayes classifier.
5.  Generated a confusion matrix.
6.  Evaluated model performance using Precision and Recall.
7.  Interpreted results for scouting applications.

## Performance Metrics

Update this section after running the notebook.

-   Precision: `XX.XX`
-   Recall: `XX.XX`

These metrics help assess the model's usefulness for scouting decisions.

## Independence Assumption

Gaussian Naive Bayes assumes that features are conditionally independent
given the class label. In basketball analytics, this assumption is often
violated because many statistics are correlated.

Examples include:

-   Points scored and minutes played
-   Assists and turnovers
-   Rebounds and efficiency ratings

Although the assumption is unrealistic, Naive Bayes can still provide
competitive predictive performance.

## Limitations

-   Sensitive to violations of feature independence.
-   May not capture complex relationships among player statistics.
-   Should not replace expert scouting evaluations.

## Recommendations

The model is best used as a supporting tool in the scouting workflow.

Suggested use cases: - Screening large numbers of prospects. -
Identifying potentially overlooked talent. - Complementing traditional
scouting reports.

## Repository Contents

-   `naive_bayes_nba.ipynb` -- Jupyter notebook containing the analysis.
-   `README.md` -- Project documentation.
-   `extracted_nba_players_data.csv` -- Engineered dataset.
