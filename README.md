# [Outlier detection in financial market data](https://github.com/dgwalters-1974/Streamlit_outliers)
Finding outliers in daily financial time series data with a selection of unsupervised learning algorithms. This toy dataset is a subset of the much larger one
used in practice, the nature of which makes it prone to human error when entries are recorded. The goal here is to establish a threshold which strikes a balance between
highlighting anomalous points whilst not triggering warnings on a daily basis as each investigation is costly in terms of time and effort. The nature of the problem
dictates that the number of positives is governed by a contamination rate set by the user and determined by domain specific factors. Algorithms investigated include
K=nearest neighbours, Isolation Forest, Mahalanobis distance and Support Vector Machines.
* Packages: Python , Matplotlib, Numpy, Pandas, Streamlit
* All models are trialled with default parameters for an overview of how they perform on the highly correlated data
* Streamlit app built to run models on new data sets / for other currencies

<img align="left" src="https://github.com/dgwalters-1974/portfolio_site/blob/main/docs/assets/images/download.png?raw=true" alt="My Image">

![chart](https://github.com/dgwalters-1974/portfolio/blob/main/docs/assets/images/chart_new.png?raw=true)

# [Just basic perceptron and some made up data](https://github.com/dgwalters-1974/perceptron_fun)
This repository is intended as an introduction to machine learning for a curious 16yr old with little knowledge of the subject but good technical foundations and
basic computer science. The idea was to follow the original perceptron algorithm as closely as possible while highlighting the similarities it has with e.g. linear
regression and its significance as a gateway to neural networks and deep learning.
![perceptron model diagram](https://github.com/dgwalters-1974/portfolio_site/blob/main/docs/assets/images/The-Perceptron-model.png?raw=true)

# [Tennis match prediction using some simple data analysis and old school ML](https://github.com/dgwalters-1974/jup_notebook/)

![tennis imagel diagram](https://github.com/dgwalters-1974/portfolio/blob/main/docs/assets/images/chart_new.png?raw=true)

Data from the Tennis Abstract website was cleaned, preprocessed and expanded upon a starting point for match prediction. Ranking methods were explored as an
alternative to the ATP points system in order to address some of its shortcomings and then various classification algorithms were trained on the data and the results
compared. We found that...
