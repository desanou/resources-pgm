># resources-pgm
Resources on Probabilistic Graphical Models

## Contents
  * [Books](#books)
  * [Papers](#papers)
    * [Gaussian graphical models](#gaussian-graphical-models)
      * [Review](#review)
      * [Inference](#inference)
    * [Mixed graphical models](#mixed-graphical-models)
  * [R packages](#r-packages)
    * [Inference](#inference)
  
## Books
  - [**Probabilistic Graphical Models**](https://mitpress.mit.edu/books/probabilistic-graphical-models), *D. Koller and N. Friedman, 2009*
  - [**Graphical models**](https://play.google.com/store/books/details?id=mGQWkx4guhAC&rdid=book-mGQWkx4guhAC&rdot=1&source=gbs_atb&pcampaignid=books_booksearch_atb), *S L Lauritzen, 1996*
  - [**Graphical Models with R**](https://link.springer.com/10.1007/978-1-4614-2299-0), *S. Højsgaard, D. Edwards, S. Lauritzen; 2012*

## Papers

### Gaussian graphical models

#### Review
  - [**Getting Started in Probabilistic Graphical Models**](https://arxiv.org/abs/math/0608017), *E. M. Airoldi, 2007*
  - [**An Overview on the Estimation of Large Covariance and Precision Matrices**](https://arxiv.org/abs/1504.02995), *J. Fan, Y. Liao, H. Liu; 2015*, [`Review of covariance and precision matrices estimation`]
  - [**Estimation of covariance and precision matrix, network structure and a view towards systems biology**](https://doi.wiley.com/10.1002/wics.1415), *M. Kuismin, M. Sillanpää*, [`Review of methods and their associated R packages`]

#### Inference
  - [**High-dimensional graphs and variable selection with the Lasso**](https://arxiv.org/abs/math/0608017), *N. Meinshausen and P. Buhlmann, 2006*, [`Neighborhood selection`]
  - [**Sparse inverse covariance estimation with the graphical Lasso**](https://arxiv.org/abs/0708.3517), *J. Friedman and al., 2008*, [`coordinate descent algorithm`]
  - [**Exact Covariance Thresholding into Connected Components for Large-Scale Graphical Lasso**](https://arxiv.org/abs/1108.3829), *R. Mazumder and T. Hastie, 2011* [`block diagonal screening rule`]
  - [**The cluster graphical Lasso for improved estimation of gaussian graphical models**](https://arxiv.org/abs/1307.5339), *K. M. Tan and al., 2013*, [`The connected components returned by Graphical Lasso with regularization parameter $\lambda$ are the same that the clusters obtained through Single Linkage hierarchical clustering on empirical covariance with dendrogram cut at level $\lambda$.`]
  
### Mixed graphical models
  - [**Anomaly Detection and Localisation using Mixed Graphical Models**](https://arxiv.org/abs/1607.05974), *R. Laby and al, 2016*
  - 
  

## R packages

### Visualization
  - [**igraph**](https://cran.r-project.org/package=igraph)
  - [**ggraph**](https://cran.r-project.org/package=ggraph), [`with ggplots`]
  - [**networkD3**](https://cran.r-project.org/package=ggraph), [`with javascript`]

### Inference
  - [**glasso**](https://cran.r-project.org/package=glasso)
  - [**simone**](https://cran.r-project.org/package=simone)
  - [**QUIC**](https://cran.r-project.org/package=QUIC)
  - [**huge**](https://cran.r-project.org/package=huge)
  - [**stabs**](https://cran.r-project.org/package=stabs), [`stability selection`] 
  
The [CRAN Task View: gRaphical Models in R](https://cran.r-project.org/web/views/gR.html) also lists a good number of packages on R linked to graphical models.