# Credit Card Transaction Fraud Detection

Machine learning notebook for detecting fraudulent credit card transactions.

## Dataset

The dataset (`creditcard.csv`, ~150 MB) is not included in this repository because it exceeds GitHub's 100 MB file limit.
Download it from Kaggle: [Credit Card Fraud Detection (mlg-ulb/creditcardfraud)](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

The notebook fetches it automatically using `kagglehub`:

```python
import kagglehub
path = kagglehub.dataset_download("mlg-ulb/creditcardfraud")
```

## Files

- `Credit Card Fraud Detection.ipynb` — the analysis and modeling notebook
