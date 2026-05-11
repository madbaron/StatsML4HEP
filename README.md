# StatsML4HEP

A collection of Jupyter notebooks covering statistical methods and machine learning techniques used in High Energy Physics (HEP) data analysis.

## Contents

The `Stats/` directory contains the following notebooks:

| Notebook | Description |
|---|---|
| `01_maximum_likelihood_fitting.ipynb` | Introduction to Maximum Likelihood Fitting |
| `02_confidence_intervals.ipynb` | Extracting confidence regions from the log-likelihood |
| `03_bayesian_fit.ipynb` | Bayesian parameter estimation using MCMC sampling |
| `04_hypothesis_testing.ipynb` | Hypothesis testing for a signal search |

The `ML/` directory contains the following notebooks:

| Notebook | Description |
|---|---|
| `01_basics.ipynb` | Basic MLP example |
| `02_CNNs.ipynb` | Training a CNN to classify MINST images |
| `03_diffusion_models.ipynb` | Set up a diffusion model to simulate calorimeter showers |
| `04_diffusion_transformer.ipynb` | Same problem as notebook 3, but using a transformer |

## Setup

Create and activate a Python(@3.13) virtual environment, then install the required dependencies:

```bash
python3.13 -m venv venv
source venv/bin/activate    # on Windows: venv\Scripts\activate
                            # on fish shell source venv/bin/activate.fish
pip install -r requirements.txt
```

Launch Jupyter to run the notebooks:

```bash
jupyter notebook
```
