# 📌 IMPORTANT NUMPY FUNDAMENTALS FOR DATA SCIENCE

SOURCE = (https://numpy.org/devdocs/reference/index.html)

# NumPy Fundamentals
 ============Table of Contents==============
- Creating Numpy Array 
- Array Arrtibutes
- Changing Datatype
- Array Opertations
- Array Functions
- Indexing and Slicing
- Iterating
- Reshaping
- Stacking
- Spliting

- `AND DID PRACTICES`

---

# 📌 NumPy Advanced Fundamentals
LIKE
- Numpy array vs Python lists
- Comparasion python list and numpy array on the basis of memory
- Advanced Indexing and Slicing
- Broadcasting Concepts
- Broadcasting Rules
- Working with mathematical formulas
    - Sigmod Function
    - Mean Squared Error Function
    - Binary Cross Entropy Loss Function
- Working with missing values 
- Plotting Graphs

---

# 📌 Numpy Advanced Method And Function Practices
## CONTENTS

`np.sort`<br>
Return a sorted copy of an array.<br>
https://numpy.org/doc/stable/reference/generated/numpy.sort.html
---
`np.append`<br>
The numpy.append() appends values along the mentioned axis at the end of the array.<br>
https://numpy.org/doc/stable/reference/generated/numpy.append.html
---
`np.concatenate`<br>
numpy.concatenate() function concatenate a sequence of arrays along an existing axis.<br>
https://numpy.org/doc/stable/reference/generated/numpy.concatenate.html
---
`np.unique`<br>
With the help of np.unique() method, we can get the unique values from an array given as parameter in np.unique() method.<br>
https://numpy.org/doc/stable/reference/generated/numpy.unique.html/
---
`np.expand_dims`<br>
With the help of Numpy.expand_dims() method, we can get the expanded dimensions of an array.<br>
https://numpy.org/doc/stable/reference/generated/numpy.expand_dims.html
---
`np.where`<br>
The numpy.where() function returns the indices of elements in an input array where the given condition is satisfied.<br>
https://numpy.org/doc/stable/reference/generated/numpy.where.html
---
`np.argmax`<br>
The numpy.argmax() function returns indices of the max element of the array in a particular axis.<br>
https://numpy.org/doc/stable/reference/generated/numpy.argmax.html
---
`np.cumsum`<br>
numpy.cumsum() function is used when we want to compute the cumulative sum of array elements over a given axis.<br>
https://numpy.org/doc/stable/reference/generated/numpy.cumsum.html
---
`np.percentile`<br>
numpy.percentile()function used to compute the nth percentile of the given data (array elements) along the specified axis.<br>
https://numpy.org/doc/stable/reference/generated/numpy.percentile.html
---
`np.histogram`<br>
Numpy has a built-in numpy.histogram() function which represents the frequency of data distribution in the graphical form.<br>
https://numpy.org/doc/stable/reference/generated/numpy.histogram.html
---
`np.corrcoef`<br>
Return Pearson product-moment correlation coefficients.<br>
https://numpy.org/doc/stable/reference/generated/numpy.corrcoef.html
---
`np.isin`<br>
With the help of numpy.isin() method, we can see that one array having values are checked in a different numpy array having different elements with different sizes.<br>
https://numpy.org/doc/stable/reference/generated/numpy.isin.html
---
`np.flip`<br>
The numpy.flip() function reverses the order of array elements along the specified axis, preserving the shape of the array.<br>
https://numpy.org/doc/stable/reference/generated/numpy.flip.html
---
`np.put`<br>
The numpy.put() function replaces specific elements of an array with given values of p_array. Array indexed works on flattened array.<br>
https://numpy.org/doc/stable/reference/generated/numpy.put.html
---
`np.delete`<br>
The numpy.delete() function returns a new array with the deletion of sub-arrays along with the mentioned axis.<br>
https://numpy.org/doc/stable/reference/generated/numpy.delete.html
---
### set functions
    np.union1d
    np.intersect1d
    np.setdiff1d
    np.setxor1d
---
`np.clip`<br>
numpy.clip() function is used to Clip (limit) the values in an array.<br>
https://numpy.org/doc/stable/reference/generated/numpy.clip.html
---
`np.swapaxes`<br>
np.swapaxes() is used to interchange two axes (dimensions) of an array.
---
`np.random.uniform`<br>
np.random.uniform() is used to generate random numbers from a uniform distribution (all values have equal probability within a range).
---
`np.count_nonzero`<br>
np.count_nonzero() is used to count the number of non-zero (non-False) elements in an array.
---

---

# NumPy Used in Data Science Projects
## 📌 Overview

Data cleaning is a crucial step in the data analysis pipeline. It ensures that the dataset is accurate, consistent, and reliable for further analysis or modeling. In this notebook, we focus on handling missing values and outliers using NumPy.

Missing data can occur due to human errors, data corruption, or issues during data collection. If not handled properly, it can significantly affect the performance of analytical models.

---

## 🎯 Objectives

* Identify and handle missing data
* Apply various imputation techniques
* Detect and treat outliers
* Prepare clean data for machine learning models

---

## 🧹 Data Cleaning Techniques

### 1. Handling Missing Data

We use `numpy.nan` to represent missing values and apply the following methods:

* **Detection:**
  `np.isnan()` is used to identify missing values.

* **Replacement:**
  `np.nan_to_num()` replaces NaN values with zero.

* **Deletion:**
  `np.delete()` removes rows/columns containing missing values.

* **Imputation:**
  Missing values are replaced with statistical measures like mean.

---

### 2. Methods to Handle Missing Data

* **Deletion:** Remove rows/columns with missing values
* **Imputation:** Replace with mean or constant values
* **Interpolation:** Estimate based on nearby values
* **Prediction:** Use models to predict missing values

---

## 📊 Outlier Detection and Treatment

Outliers can distort analysis results, so we apply multiple techniques:

### ✔ Z-Score Method

* Calculates deviation from mean using standard deviation
* Removes values beyond a threshold (e.g., z > 2)

### ✔ Percentile Clipping

* Uses `np.percentile()` and `np.clip()`
* Restricts values within a defined percentile range

### ✔ Median-Based Filtering

* Replaces extreme values with the median
* Uses percentile thresholds to detect outliers

---

## 🤖 Integration with Machine Learning

NumPy integrates seamlessly with libraries like Scikit-learn.
We demonstrated a simple Linear Regression model using `LinearRegression` to show how cleaned data can be used for predictions.

---

## 🧪 Example Outcome

* Missing values successfully handled
* Outliers detected and removed
* Clean dataset ready for modeling
* Model prediction example: Input = 6 → Output = 12

---

# Best 50 NumPy Functions For Data Science

**========𝗧𝗔𝗕𝗟𝗘 𝗢𝗙 𝗖𝗢𝗡𝗧𝗘𝗡𝗧========**
- Array Creation Methods
- Array Operations
- Replacing Values Inside Array
- Set Operations
- Splitting
- Stacking
- Comparing Two Arrays
- Repeating Array Elements
- Einstein Summation Conventions
- Statistical Analysis
- Array Printing Options
- Save and Load Array Data