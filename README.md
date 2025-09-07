Link: https://github.com/imamirkhan/PA_Directed_Marketing/blob/main/prompt_III.ipynb

# Marketing Campaign Conversion - Comparing various models

This project trains and compares multiple classification models to predict whether a client subscribes to a term deposit.


## Files

- 'prompt_III.ipynb': Main Jupyter Notebook containing all analysis, visualizations, and modeling.
- 'output.html' : Contains data profile
- 'data folder' : Contains bank-additional-full.csv which has data related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls.
- 'README.md': Project overview and summary of findings.

## Modeling Summary

- Logistic Regression, SVM, Decision Tree & KNN
- Hyperparameter tuning was done via GridSearchCV.
- Models were evaluated using Accuracy, Precision, Recall & F1


## Key Findings

- Logistic Regression was best performing model.
- High employment variance is the biggest negative indicator for conversion
- May & June are the next biggest negative indicator for conversion. Portugal tax season is from April to June.
- The month March which is the month before the tax season is the biggest indicator for conversion.
- Consumer price Index is positively linked to conversion as people try to fight inflation with term deposit on savings.
- The retiree group also stood out for more coversion.

## How to Run

1. Clone this repository.
2. Open 'prompt_III.ipynb' in Jupyter Notebook.
3. Run all cells from top to bottom.

## Contact

For questions open an issue or contact via GitHub.

