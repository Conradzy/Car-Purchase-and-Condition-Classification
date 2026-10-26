# Car Purchase and Used-Car Condition Classification

Runs a reusable classification pipeline on two automotive datasets: whether a customer will buy a car and the condition class of a used car. Numeric and categorical preprocessing are combined with three supervised classifiers.

## Workflow

1. Load the car-purchase and used-car-condition datasets.
2. Inspect schemas, missing values, and class distributions.
3. Preprocess numeric and categorical columns with a column transformer.
4. Train Logistic Regression, Random Forest, and SVM models.
5. Compare accuracy, classification reports, confusion matrices, and the best model per task.

## Data Requirements

- `car_purchase_classification_200.csv`
- `used_car_condition_classification_200.csv`

Datasets and generated artifacts are not included unless they are embedded directly in the notebook.

## Requirements

- pandas
- NumPy
- scikit-learn
- Matplotlib

Install missing packages in your Jupyter or Google Colab environment before running the notebook.

## Running the Notebook

1. Open [`classificationanalysisnapinas.ipynb`](classificationanalysisnapinas.ipynb) in Jupyter Notebook or Google Colab.
2. Place any required data files in the path expected by the notebook.
3. Update local or Google Drive paths where needed.
4. Run the cells from top to bottom.

## Outputs

- Per-model metrics
- Confusion matrices
- Combined results table
- Best-model summary for each dataset

## Repository Contents

```text
.
|-- README.md
`-- classificationanalysisnapinas.ipynb
```

## Notes

- This repository preserves the analysis as a notebook-first educational project.
- Results may vary with dataset versions, random splits, package versions, and available hardware.
- Review file paths and runtime-specific commands before executing outside Google Colab.
