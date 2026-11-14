# DSC8307 Data Mining, Modeling and Analytics — Assignment 2

**Student:** Namuyomba Nakachwa Emilly · **Registration number:** S25M19/047 · **Access number:** B35963

| File | Contents |
|---|---|
| `wholesale_customers_Project_1.ipynb` | Project 1: segmenting wholesale customers (cluster tendency; partitioning vs hierarchical vs density-based clustering; named segments) |
| `credit_card_fraud_Project_2.ipynb` | Project 2: anomaly detection to prioritise fraud investigations (statistical baseline; cluster-based vs classification-based detectors) |
| `requirements.txt` | Python libraries needed to run the notebooks |

## Data
The datasets are provided in the assignment materials and are **not included** in this repository (`creditcard.csv` is 151 MB, above GitHub's 100 MB file limit). To re-run the notebooks, place `wholesale-customers.csv` and `creditcard.csv` in the same folder as the notebooks. All outputs shown in the notebooks come from complete runs.

## How to run
```
pip install -r requirements.txt
jupyter notebook
```
Open a notebook and choose **Kernel → Restart & Run All**. Random seeds are fixed (`SEED = 42`).

## Data sources
- Cardoso, M. G. M. S. (2014). Wholesale customers [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5030X
- Machine Learning Group, Université Libre de Bruxelles. Credit Card Fraud Detection dataset (Dal Pozzolo et al., 2015), as provided with the assignment.
