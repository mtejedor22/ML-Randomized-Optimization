# Randomized Optimization

## Introduction
This repository contains Python code for conducting experiments on three different optimization problems using randomized optimization algorithms. The problems considered are Continuous Peaks, Flip Flop, and Four Peaks. The algorithms investigated include Simulated Annealing, Randomized Hill Climb, Genetic Algorithm, and MIMIC (Mutual Information Maximization for Input Clustering).

For acessing the files through Georgia Tech affiliation use the following link: [https://gatech.box.com/s/4nhqthiv4j27vksn99x0wmcx555p3ixk](https://gatech.box.com/s/pq3ykfkxqt7e0sbtr5f55593v6a0a3xf)

## Dependencies
Before running the code, make sure to install the required library using the following command:

```bash
pip install git+https://github.com/hiive/mlrose.git
```
```bash
pip install scikit-learn
```
```bash
pip install pandas
```
```bash
pip install numpy
```
```bash
pip install matplotlib
```
## Dataset

1. **Breast Cancer Dataset:**
   - Dataset file: [`wdbc.data`](wdbc.data)
   - Features (`X_cancer`): All columns except the first one
   - Labels (`y_cancer`): 'M' (Malignant) or 'B' (Benign)

## Usage

1. Open the Jupyter Notebook ([`RO_Assigment2.ipynb`](RO_Assigment2.ipynb)) in a compatible environment (e.g., Google Colab).
2. Adjust the file paths for the dataset (`file_path_cancer`) if needed.
3. Run the cells sequentially to execute the code and observe the results.
