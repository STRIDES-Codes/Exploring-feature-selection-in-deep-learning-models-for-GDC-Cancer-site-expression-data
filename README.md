# 2020 CSHL Codeathon
## *Exploring Feature Selection for Genomics Expression Profile*


### Motivation: 

NCI-DOE collaboration (https://github.com/ravichas/ML-TC1) show that expression profiles collected from different cancer sites can be modeled (classification) using the deep-learning (convolutional neural network) method. The method works well for a balanced dataset. What is not clear is, the neural network method doesn't answer what features (i.e. genes) are important and provide a signal to the model? A project to explore feature selection for genomics data could be useful for cancer research communities.

### Complexity of the problem and open questions:

* Genomics data is high dimensional in terms of the number of genes/probes/features. Most models constructed from a high dimensional data will be complex. Identifying important features/genes is as important as building high accuracy models. Keeping in mind that genes do not work alone, pathway-based analysis could be used to 

## Overview 
* Data collection 
  * Data source will be Genmic Data Commons. Several datasets (cancer sites that have same lineages and different lineages) will be constructed.
* Datasets created in the previous step will be used to construcct/compare several supervised and unsupervised models. 
* Important features from these models will be compared with experimental findings
* Summarize the conclusions
* Provide list of open questions and propose future directions
