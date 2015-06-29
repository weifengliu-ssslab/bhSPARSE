bhSPARSE: A Sparse BLAS Library
========

<br><hr>
<h3>Introduction</h3>

The bhSPARSE provides basic linear algebra subroutines (BLAS) used for sparse matrix computations on heterogeneous parallel processors. Currently, the bhSPARSE library is under-developing. However, some important building blocks have their source code available.

<br><hr>
<h3>SpMV and SpGEMM for Benchmarking</h3>

<h5>1. Sparse Matrix-Vector Multiplication (SpMV) on Intel CPUs, nVidia GPUs, AMD GPUs and Intel Xeon Phi using the CSR5 format</h5>

<b>Code repository</b>: <a href="https://github.com/bhSPARSE/Benchmark_SpMV_using_CSR5">https://github.com/bhSPARSE/Benchmark_SpMV_using_CSR5</a>

<b>Paper</b>: Weifeng Liu and Brian Vinter, "CSR5: An Efficient Storage Format for Cross-Platform Sparse Matrix-Vector Multiplication". In Proceedings of the 29th ACM international conference on Supercomputing (ICS '15), pp.339-350, 2015. 
[<a href="http://www.nbi.dk/~weifeng/papers/CSR5_Liu_ics15.pdf">pdf</a>][<a href="http://www.nbi.dk/~weifeng/slides/CSR5_Liu_ics15_slides.pptx">slides</a>]

<h5>2. Sparse Matrix-Vector Multiplication (SpMV) on Intel, AMD and nVidia heterogeneous processors using the CSR format</h5>

<b>Code repository</b>: <a href="https://github.com/bhSPARSE/Benchmark_SpMV_using_CSR">https://github.com/bhSPARSE/Benchmark_SpMV_using_CSR</a>

<b>Paper</b>: Weifeng Liu and Brian Vinter, "Speculative Segmented Sum for Sparse Matrix-Vector Multiplication on Heterogeneous Processors". Parallel Computing, 2015. (accepted April 2015)
[<a href="http://www.nbi.dk/~weifeng/papers/SpMV_Liu_parco.pdf">pdf</a>]

<h5>3. Sparse Matrix-Matrix Multiplication (SpGEMM) on GPUs and Heterogeneous Processors using the CSR format</h5>

<b>Code repository</b>: <a href="https://github.com/bhSPARSE/Benchmark_SpGEMM_using_CSR">https://github.com/bhSPARSE/Benchmark_SpGEMM_using_CSR</a>

<b>Paper (1)</b>: Weifeng Liu and Brian Vinter, "An Efficient GPU General Sparse Matrix-Matrix Multiplication for Irregular Data" Parallel and Distributed Processing Symposium, 2014 IEEE 28th International (IPDPS '14), pp.370-381, 19-23 May 2014. [<a href="http://www.nbi.dk/~weifeng/papers/SpGEMM_Liu_ipdps14.pdf">pdf</a>][<a href="http://www.nbi.dk/~weifeng/slides/SpGEMM_Liu_ipdps14_slides.pptx">slides</a>]

<b>Paper (2)</b>: Weifeng Liu and Brian Vinter, "A Framework for General Sparse Matrix-Matrix Multiplication on GPUs and Heterogeneous Processors". Journal of Parallel and Distributed Computing (JPDC), 2015. (accepted June 2015) (Extended version of the IPDPS '14 paper) [<a href="http://www.nbi.dk/~weifeng/papers/SpGEMM_Liu_jpdc.pdf">pdf</a>]

<br><hr>
<h3>Contact</h3>

<a href="http://www.nbi.dk/~weifeng/">Weifeng Liu</a> and Brian Vinter (vinter _at_ nbi.ku.dk).



