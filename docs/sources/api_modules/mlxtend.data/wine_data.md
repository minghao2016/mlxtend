## wine_data

*wine_data()*

Wine dataset.


- `Source` : https://archive.ics.uci.edu/ml/datasets/Wine


- `Number of samples` : 178


- `Class labels` : {0, 1, 2}, distribution: [59, 71, 48]


    Dataset Attributes:

    - 1) Alcohol
    - 2) Malic acid
    - 3) Ash
    - 4) Alcalinity of ash
    - 5) Magnesium
    - 6) Total phenols
    - 7) Flavanoids
    - 8) Nonflavanoid phenols
    - 9) Proanthocyanins
    - 10) Color intensity
    - 11) Hue
    - 12) OD280/OD315 of diluted wines
    - 13) Proline

**Returns**

- `X, y` : [n_samples, n_features], [n_class_labels]

    X is the feature matrix with 178 wine samples as rows
    and 13 feature columns.
    y is a 1-dimensional array of the 3 class labels 0, 1, 2
