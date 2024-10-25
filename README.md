# [Streamlit app for detecting outliers in interest rate swaps / fra data](https://github.com/dgwalters-1974/Streamlit_outliers)
Investigating outliers in daily financial time series data with a selection of unsupervised learning algorithms. This toy dataset is a subset of the much larger one
used in practice, the nature of which makes it prone to human error when entries are recorded. The goal here is to establish a threshold which strikes a balance between
highlighting anomalous points whilst not triggering warnings on a daily basis as each investigation is costly in terms of time and effort. The nature of the problem
dictates that the number of positives is governed by a contamination rate set by the user and determined by domain specific factors. Algorithms investigated include
K=nearest neighbours, Isolation Forest, Mahalanobis distance and Support Vector Machines.
* Packages: Python , Matplotlib, Numpy, Pandas, Streamlit
* All models are trialled with default parameters for an overview of how they perform on the highly correlated data
* Streamlit app built to run models on new data sets / for other currencies 



