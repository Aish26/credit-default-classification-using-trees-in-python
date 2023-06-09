<h2 align="center">credit-default-classification-using-trees</h2>
<br>
<h3> 📄 Introduction</h3>
The goal of this project is to create a credit default classification model using a tree-based algorithm. The model will be trained on a dataset of past customer records, including both defaulters and non-defaulters, with the aim of predicting the likelihood of future default. Relevant features extracted from the dataset will be utilized to ensure accurate classification.
    
The response variable used is "payment_default", where a value of 1 indicates that the customer defaulted and a value of 0 represents that the customer did not default.

Tree based algorithms such as CART(Classification and Regression tree) and Random forest is applied on dataset for classification.
</br>
<h3>🔨 Tools and Techniques used</h3>

- Jupyter Notebook
- Python
- Principal Component Analysis
- Classification and Regression tree
- Random forest

<h3> 🔭 Objective</h3>

- Predict the credit default probability of a user. 

<h3>🔗 Contact Me</h3>
 <a href='https://www.linkedin.com/in/aishwarya-ucd/'><img align='center' alt="linkedin" src="https://raw.githubusercontent.com/shahbajjamil/Social-Meadia-Icons/master/Icons-logos/linkedin-circle.png" height='26px'/></a>

<h3>🔄 Model Selection Steps and Result</h3>

- EDA: The first step is to apply EDA to access null values and outliers. 
- Scaling: The data has outliers to the appropriate scaling technique is used to scale data before applying PCA. Robust scaling is chosen as it takes care of outliers.
- PCA: The number of components that explains cumulative variance of more than 80% are chosen to keep for PCA using elbow plot. 
- Logistic Regression: As this is a classification problem logistic regression is applied first.
- CART: The full and post pruned tree are both used to compare their performance.
- Random forest: It is applied with the trees size as 1000 to find a better classification accuracy.

