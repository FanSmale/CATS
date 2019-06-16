# Vmodel

Clustering-based active learning splits the data into a number of blocks and queries the labels of most the representative instances. 
When the cost of labeling and misclassification are considered, we also face a key issue: How many labels should be queried for a given block. 
In this paper, we present theoretical and practical statistical methods to handle this issue. 
The theoretical statistical method calculates the optimal number of query labels for a predefined label distribution. 
Considering label distributions for different clustering qualities, we obtain three hypothetical models, namely Gaussian, Uniform, and V models. 
The practical statistical method calculates empirical label distribution of the cluster blocks. Considering four popular clustering algorithms, we use symmetry and curve fitting techniques on 30 datasets to obtain empirical distributions. 
Inspired by three-way decision, we design an algorithm called the cost-sensitive active learning through statistical methods (CATS).
Experiments were performed on 12 binary-class datasets for both the distribution evaluation and learning task. 
The results of significance tests verify the effectiveness of CATS and its superior performance with respect to state-of-the-art cost-sensitive active learning algorithms.

doi:10.1016/j.ins.2019.06.015
