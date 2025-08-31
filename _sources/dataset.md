# Dataset

Pada bagian ini ditampilkan dataset yang digunakan dalam proyek.

```{code-cell} ipython3
import pandas as pd

# Baca dataset dari folder dataset/
df = pd.read_csv("dataset/Coimbra_breast_cancer_dataset.csv")

# Tampilkan 5 data teratas
df.head()
