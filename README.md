# Rule-Mining-with-Bayesian-Networks

This is a Machine Learning project to derive association rules from an online shopping dataset.

## Association rules
In simply terms these are just (statistical) rules that predict something. For example one of the rules that we derived in the project through the online dataset was:
"If a user buys a PACK OF SIX PAPER PLATES, he will also buy a PACK OF SIX PAPER CUPS." 
This rule makes a lot of sense considering what we know about the real world. It's very probably that the user is buying the paper plates for a get together or a party, and the user might also need paper cups for this. However, this rule has simply come from analysing the dataset, without any external information about the real world. In a way this is a good demonstration of the correctness and usefullness of this project!

## A Bayesian Association Rule Mining Algorithm
Rule mining has a well known algorithm, known as the apriori algorithm. Our project tries to implement a novel theoretical algorithm that uses Bayesian networks created on the exisiting database to make rule predicitons. We use Bayesian confidence and Bayesian lift , calculated using the BayesianNet,  as measures of "goodness" for the rules. 
This algorithm is studied and taken directly from the paper by Tian et. al. 2013, that can also be found in this repository. This algorithm is implemented on a real world dataset of online transactions in various countries. Our code chooses to study the sales in France as a demonstration, but the same code can be very easily extended to any country/ set of countries. 

## Dataset
Our dataset is an online retail dataset taken from the Machine learning archives of UC Irvine. It is freely available online. Please access it using the link:
http://archive.ics.uci.edu/ml/datasets/Online+Retail

The dataset will have to be downloaded and added to your google drive. The code requires it to be accessed through google drive using Google colab.

## Code
The working Jupyter notebook file can be found in the repository. It walks through all the steps involved, as well as the final results and observations. 

You can also access the updated working project in this [colab notebook](https://colab.research.google.com/drive/16vFwrPpfbBpGFI93LAmX2mfUhywDL9YH?usp=sharing)
