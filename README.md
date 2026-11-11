# Trade Return Modeling

| File | Contents |
|---|---|
| `train.csv.gz` | 90,000 rows: anonymized features `0`–`65` and `TARGET`, the realized return of a short-horizon trade |
| `test.enc` | 19,700 rows that come after train in time. AES-256-GCM encrypted; you need the password to decrypt it |
| `Trade_Return_Modeling.ipynb` | Starter notebook: loads the data and has a cell that unlocks the test set |

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/victorwangse/witg-qis/blob/main/Trade_Return_Modeling.ipynb)

```bash
git clone https://github.com/victorwangse/witg-qis.git
```

Unlock the test set only after your model and trade-selection rule are frozen.
