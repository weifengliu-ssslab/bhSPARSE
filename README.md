bhSPARSE: A Sparse BLAS Library
========

<br><hr>
<h3>Introduction</h3>

The bhSPARSE provides basic linear algebra subroutines (BLAS) used for sparse matrix computations on heterogeneous parallel processors. Currently, the bhSPARSE library is under-developing. However, some important building blocks have their source code available.

<br><hr>
<h3>SpMV and SpGEMM for Benchmarking</h3>

<h5>1. Sparse Matrix-Vector Multiplication (SpMV) on Intel CPUs, nVidia GPUs, AMD GPUs and Intel Xeon Phi using the CSR5 format</h5>

<b>Code repository</b>: <a href="https://github.com/bhSPARSE/Benchmark_SpMV_using_CSR5">https://github.com/bhSPARSE/Benchmark_SpMV_using_CSR5</a>

<b>Paper</b>: Weifeng Liu and Brian Vinter, "CSR5: An Efficient Storage Format for Cross-Platform Sparse Matrix-Vector Multiplication". In Proceedings of the 29th ACM international conference on Supercomputing (ICS '15), 2015. (To appear).
[<a href="http://arxiv.org/pdf/1503.05032v2.pdf">pdf</a>]

<h5>2. Sparse Matrix-Vector Multiplication (SpMV) on Intel, AMD and nVidia heterogeneous processors using the CSR format</h5>

<b>Code repository</b>: <a href="https://github.com/bhSPARSE/Benchmark_SpMV_using_CSR">https://github.com/bhSPARSE/Benchmark_SpMV_using_CSR</a>

<b>Paper</b>: Weifeng Liu and Brian Vinter, "Speculative Segmented Sum for Sparse Matrix-Vector Multiplication on Heterogeneous Processors". Parallel Computing, 2015. (accepted April 2015)
[<a href="http://arxiv.org/pdf/1504.06474v1">pdf</a>]

<h5>3. Sparse Matrix-Matrix Multiplication (SpGEMM) on GPUs and Heterogeneous Processors using the CSR format</h5>

<b>Code repository</b>: <a href="https://github.com/bhSPARSE/Benchmark_SpGEMM_using_CSR">https://github.com/bhSPARSE/Benchmark_SpGEMM_using_CSR</a>

<b>Paper (1)</b>: Weifeng Liu and Brian Vinter, "An Efficient GPU General Sparse Matrix-Matrix Multiplication for Irregular Data," Parallel and Distributed Processing Symposium, 2014 IEEE 28th International (IPDPS '14), pp.370-381, 19-23 May 2014. [<a href="http://hiperfit.dk/pdf/SpGEMM_Liu_ipdps14.pdf">pdf</a>][<a href="http://hiperfit.dk/pdf/SpGEMM_Liu_ipdps14_slides.pptx">slides</a>]

<b>Paper (2)</b>: Weifeng Liu and Brian Vinter, "A Framework for General Sparse Matrix-Matrix Multiplication on GPUs and Heterogeneous Processors," Extended version of paper (1) submitted to Journal of Parallel and Distributed Computing (JPDC), 2015. [<a href="http://arxiv.org/pdf/1504.05022v1.pdf">pdf</a>]

<br><hr>
<h3>Contact</h3>

Weifeng Liu (weifeng.liu _at_ nbi.ku.dk) and Brian Vinter (vinter _at_ nbi.ku.dk).



