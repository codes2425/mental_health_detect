## Mental Health Detection — Notebooks and Data

Short and focused collection of notebooks and datasets used for mental health detection experiments (balanced/unbalanced datasets, oversampling and undersampling experiments, and evaluation metrics).

### Project Contents
- `kappa_calculation.ipynb` — notebook to compute inter-annotator agreement (Cohen's kappa) / evaluation scripts.
- `oversampled_experiments.ipynb` — experiments using oversampling techniques.
- `undersampled_experiments.ipynb` — experiments using undersampling techniques.
- `model_results_balanced.csv` — model output / metrics for balanced training.
- `model_results_unbalanced.csv` — model output / metrics for unbalanced training.
- `train_data_balanced.csv` — balanced training dataset.
- `train_data_unbalanced.csv` — unbalanced training dataset.
- `test_data.csv` — test dataset used for evaluation.
- `manual_annotation_data.csv` — human-annotated data used for validation.

### Quick Setup

1. Clone the repository:

```bash
git clone <repo-url>
cd mental_health_detect
```

2. Create and activate a Python virtual environment:

```bash
python -m venv venv
source venv/Scripts/activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

### Run the Notebooks

Start Jupyter and open the notebooks in a browser:

```bash
jupyter notebook
```

Open the notebook you want (for example `oversampled_experiments.ipynb`) and run the cells top-to-bottom to reproduce experiments and figures.

### Notes

- The repository contains Jupyter notebooks and CSV data files.
- `requirements.txt` contains commonly used packages inferred from the notebooks. If you run into a missing package error, install the package shown in the error and re-run.
- If you prefer Docker or conda, adapt the environment creation to your preferred workflow.
