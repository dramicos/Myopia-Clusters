# Myopia-Clusters
Applying unsupervised machine learning to see if different groups of people are at risk of developing myopia.

### Produced by:
* Arnold Schultz

# Overview:
This is a quick study to see if any clusters can be found in a longitudinal study for the development of myopia to potentially predict who may be at risk.  The idea is to see if patients can be grouped according to their risk. 

## Tools used
Principal component analysis (PCA):  Linear reduction of dimentionality via projection and can be used to preserve a specified degree of explainability in the data.  Note: This method does not work with sparse data

T-distributed Stochastic Neighbor Embedding:  For visuallizing high-dimensional data by converting similarities in data points to joint probabilities.  It is not a convex function and thus different initizations can get different results.


## References

1. Reduced dataset from [Orinda Longitudinal Study of Myopia conducted by the US National Eye Institute](https://clinicaltrials.gov/ct2/show/NCT00000169)
1. https://scikit-learn.org/ user guide for information on models/tools.