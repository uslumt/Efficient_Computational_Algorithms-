# The Decompositional Approach To Matrix Computation

In this repo, six most commonly used matrix factorization algorithms are investigated as a semester project for Efficient Computational Algorithms 2022 WS at USI Università della Svizzera italiana.
The main reference can be found [here](https://www.cs.fsu.edu/~lacher/courses/COT4401/notes/cise_v2_i1/matrix.pdf).

## Introduction 
As technogy has been rapidly improved, machines have to analyze much more data than in the past. By means data is a matrix with bunch of elements for example; images, variables to estimate price of a houses. Last decades researchers came up with new techniques such as Machine Learning models to deal with huge datasets, however when the vast majority of these state of the art algorithms are considered, it can be seen that main numerical problem to solve is A*x = b where generally the the equation is solved for vector x.
In this project, the matrix A in the linear equation above can be factorized by at least two usefull matrices wich gives some interesting facts about the matrix.

## Work Done 
* Studied different approaches of the matrix factorization
* Literature review
* Code Python and Matlab scrips 

## Results 

| Algorithm  | Outcome |
| ------------- | ------------- |
| QR-Householder  | 1.000000284809481  |
|QR-Gram-Schmidt  | 0.981779891867633  |
| Cholesky   | -0.390537644183687  |
| Singular Value Decomposition  | 1.000000284809170  |
| LUP  | 0.999999951596828   |

**table 1 :** *Vandermonde Least Squares Problem Results* 

Acording to [Lloyd N. Trefethen and David Bau](https://people.maths.ox.ac.uk/trefethen/text.html) the absolutely close Outcome to true value 1 the more stable algorithm is.


| ![Speed](https://github.com/uslumt/Efficient_Computational_Algorithms/blob/main/Result/figures/Computation_time_identity.png) |
|:--:| 
  |**figure 1 :** *Computation speed comparison of different factorization algorithms*|

For more results, elaboration and possible comparisons please check [Notebook](https://github.com/uslumt/Efficient_Computational_Algorithms/blob/main/Main.ipynb)
## Requirements
* Jupyter Notebook
* Python >= 3.6
* Matlab

## Future Work 
This project is designed for future extencions and it can be seen that the datasets are publicly available. Especially [Symmetric Positive Definite](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_sparse_spd_matrix.html#sklearn.datasets.make_sparse_spd_matrix) matrix dataset has some pitfalls.
It can be investigated with custom datasets and some improved factorization algorithms.

**Authors**  
Muhammet USLU @ USI & FAU  
Mao Yen PO  @ USI & FAU

