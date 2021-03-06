# Kernel Treelets (KT)

Kernel Treelets is a hierarchical clustering algorithm proposed by Hedi Xia and Hector D. Ceniceros. 
It combines treelets, a particular multiscale decomposition of data, with a projection on a reproducing kernel Hilbert space. 
The proposed approach, called kernel treelets (KT), effectively substitutes the correlation coefficient matrix used in treelets with a symmetric, 
positive semi-definite matrix efficiently constructed from a kernel function. 
Unlike most clustering methods, which require data sets to be numeric, 
KT can be applied to more general data and yield a multi-resolution sequence of basis on the data directly in feature space. 
A more detailed explanation about Kernel Treelets can be found in arXiv (https://arxiv.org/abs/1812.04808). 
The paper is accepted by Advances in Data Science and Adaptive Analysis.
The most recent test version is at https://github.com/hedixia/KernelTreelets_v5.

Examples in the paper are included as jupyter notebooks. 
The implementation may not be fully optimized. 
Prior to running the notebooks, you may need to install Kernel Treelets with command ```pip install KernelTreelets```.

For more infomation about Kernel Method, see (https://en.wikipedia.org/wiki/Kernel_method).

For more infomation about Treelets by Ann B. Lee, Boaz Nadler and Larry Wasserman, see arXiv (https://arxiv.org/abs/0707.0481).
