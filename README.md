## 2023 전력사용량 예측 AI 경진대회
https://dacon.io/competitions/official/236125/overview/description

## Environment
```
Windows 11 Home
CPU: 13th Gen Intel(R) Core(TM) i9-13900H
RAM: 64GB
GPU: NVIDIA GeForce RTX 4060 Laptop GPU
```

## Library
```
polars 0.18.4
pandas 1.5.3
numpy 1.24.3
matplotlib 3.7.1
seaborn 0.12.2
xgboost 1.7.6
catboost 1.2
treelite 3.9.0
```

## Directory
```
├── data
│   ├── dataset
│   │   ├── EE_DATASET_144
│   │   │   └── ...
│   ├── model
│   │   ├── EE_TRAIN_144_0
│   │   │   ├── ...
│   │   ├── EE_TRAIN_144_1
│   │   │   └── ...
│   │   └── EE_TRAIN_144_2
│   │       └── ...
│   ├── train.csv
│   └── test.csv
├── EE_DATASET.ipynb
├── EE_INFERENCE.ipynb
├── EE_TRAIN_0.ipynb
├── EE_TRAIN_1.ipynb
└── EE_TRAIN_2.ipynb
```

## Order
```
1. EE_DATASET.ipynb
2.
  - EE_TRAIN_0.ipynb
  - EE_TRAIN_1.ipynb
  - EE_TRAIN_2.ipynb
3. EE_INFERENCE.ipynb
