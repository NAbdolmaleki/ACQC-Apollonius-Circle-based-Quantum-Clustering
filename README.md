# ACQC: Apollonius Circle-based Quantum Clustering

The Quantum Clustering (QC) method begins by generating a wave function for estimating the data points’ density distribution, which is the sum of Gaussian kernels to the data points’ centers. It then forms the corresponding potential function and finally locates clusters, emphasizing the potential function’s minimums. This process is highly sensitive to the kernel bandwidth in the Schrödinger equation that controls the shape of the Gaussian kernel and affects the clustering result. This paper proposes an Apollonius Circle-based Quantum Clustering (ACQC) method, which adaptively and automatically sets the kernel bandwidth without any prior knowledge regarding the data points and clusters. ACQC is the first attempt to achieve such an adaptive kernel bandwidth through the Apollonius region’s neighborhood construction. The wave function is estimated based on data points in the neighborhood group constructed by Apollonius circles to optimize ACQC calculations. The experimental results of ACQC compared to the original QC method indicate an improvement in calculation efficiency by approximately a 38.3% reduction in terms of running time and a 41.17% improvement in detecting the correct number of clusters. Extensive experiments on four synthetic and 20 real-world datasets show that ACQC outperforms state-of-the-art methods significantly. 

![NewACQC](https://user-images.githubusercontent.com/15902165/166266088-af8b12b3-1f51-4e5f-91fc-0355894b7a05.jpeg)


The ACQC repository includes the MATLAB implementation of the ACQC and original QC methods.
The SourceCode contains three folders:
1. MainACQC: for running the code you, start with ACQCscript.m as the main script of the ACQC method.
2. OrginalQC: for running the code you start with QCscript.m as the main script of the original QC method.
3. CTPandTPs: the scripts in this folder separately show how the Target Points (TPs) and Candidate Target Points (CTPs) are detected.



# Condition and terms to use any sources of this project (Codes, Datasets, etc.):

1.	Please cite the following paper:
N.Abdolmaleki, L.Mohammad Khanli, M.Hashemzadeh, S.Pourbahrami, ACQC: Apollonius Circle-based Quantum Clustering, Journal of Computational Science,64 (2022)101877.
2.	Please do not distribute the database or source codes to others without the authorization from Dr. Mahdi Hashemzadeh (Corresponding author).
Authors’ Emails: N.abdolmaleki@tabrizu.ac.ir (N. Abdolmaleki), l-khanli@tabrizu.ac.ir (L. M. Khanli), hashemzadeh@azaruniv.ac.ir (M. Hashemzadeh), sh.pourbahrami@tabrizu.ac.ir (S. Pourbahrami).

Also for use of the Original QC code please cite the below papers:
*D. Horn and A. Gottlieb, “The method of quantum clustering,” Adv. Neural Inf. Process. Syst., no. 1, 2002, DOI: 10.7551/mitpress/1120.003.0103
*D. Horn and A. Gottlieb, “Algorithm for Data Clustering in Pattern Recognition Problems Based on Quantum Mechanics,” Phys. Rev. Lett., vol. 88, no. 1, p. 4, 2002, DOI: 10.1103/PhysRevLett.88.018702.
