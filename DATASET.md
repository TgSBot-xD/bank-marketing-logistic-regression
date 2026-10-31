# Dataset attribution

This repository includes **`bank-full.csv`** from the `bank.zip` archive in
[UCI Bank Marketing](https://archive.ics.uci.edu/dataset/222/bank+marketing).
It contains 45,211 records, 16 input variables, and the target column `y`.
The experiment uses eight of those input variables.

## Citation

Moro, S., Rita, P., & Cortez, P. (2014). *Bank Marketing* [Dataset].
UCI Machine Learning Repository. https://doi.org/10.24432/C5K306.

## License and modifications

UCI lists the dataset under the
[Creative Commons Attribution 4.0 International license (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
The CSV is redistributed unchanged from the file uploaded for this experiment.
Feature selection, target encoding, splitting, and scaling happen in notebook memory;
they do not modify the CSV. This dataset license applies to the data, not automatically
to all code in the repository.

## Restore the input

1. Open the UCI dataset page and download its archive.
2. Open the nested `bank.zip` and extract **`bank-full.csv`** into the repository root.
3. Use `sep=";"` when reading it with pandas.

`bank.csv`, `bank-additional.csv`, and `bank-additional-full.csv` are different
variants and do not reproduce this experiment.

SHA-256 of the included CSV:

```text
d1513ec63b385506f7cfce9f2c5caa9fe99e7ba4e8c3fa264b3aaf0f849ed32d
```
