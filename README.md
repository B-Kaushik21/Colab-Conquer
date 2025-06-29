# Colab-Conquer
The analysis includes:
- Loading and displaying the dataset
- Generating summary statistics using `.describe()`
- Calculating mean, median, and standard deviation
- Visualizing the distribution of features (can be added using matplotlib)

## 📁 Dataset Source
The dataset is loaded directly from [this URL](https://bit.ly/4nejNue).

## 📌 Run in Google Colab
You can open and run this notebook in Google Colab using the badge below:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/B-Kaushik21/Colab-Conquer/blob/main/Colab_&_Conquer.ipynb)

## 🛠️ Requirements
- Python
- pandas
- matplotlib

These libraries are standard in Google Colab, so no need for manual installation.

## 💡 Example Output
- Summary statistics of the dataset
- Mean, Median, and Standard Deviation values printed to the console
```First 5 rows of the dataset:
   sepal_length  sepal_width  petal_length  petal_width species
0           5.1          3.5           1.4          0.2  setosa
1           4.9          3.0           1.4          0.2  setosa
2           4.7          3.2           1.3          0.2  setosa
3           4.6          3.1           1.5          0.2  setosa
4           5.0          3.6           1.4          0.2  setosa

 Dataset Description (.describe()):
       sepal_length  sepal_width  petal_length  petal_width
count    150.000000   150.000000    150.000000   150.000000
mean       5.843333     3.057333      3.758000     1.199333
std        0.828066     0.435866      1.765298     0.762238
min        4.300000     2.000000      1.000000     0.100000
25%        5.100000     2.800000      1.600000     0.300000
50%        5.800000     3.000000      4.350000     1.300000
75%        6.400000     3.300000      5.100000     1.800000
max        7.900000     4.400000      6.900000     2.500000

 Mean of each column:
sepal_length    5.843333
sepal_width     3.057333
petal_length    3.758000
petal_width     1.199333
dtype: float64

 Median of each column:
sepal_length    5.80
sepal_width     3.00
petal_length    4.35
petal_width     1.30
dtype: float64

 Standard Deviation of each column:
sepal_length    0.828066
sepal_width     0.435866
petal_length    1.765298
petal_width     0.762238
dtype: float64
```
![image](https://github.com/user-attachments/assets/dd29d0b6-8282-4aba-af07-b0a434f22c07)



