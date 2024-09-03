<!--StartFragment-->

**RNAseq in relation to Data Science and Machine Learning** 

**Introduction**

RNA sequencing (RNAseq) is an important technology in cancer research and is used to analyse the transcriptome. This is the total set of RNA transcripts assembled by the genome. RNAseq has the ability to offer a great insight into the molecular processes underlying cancer. It works by comparing the gene expression profiles between normal tissues and cancerous. This technique detects the differentially expressed genes that may be responsible for initiation, progression and metastasis of cancer. For instance, upregulated genes may contribute to cell proliferation whereas downregulated genes may be associated with apoptosis or immune responses. Moreover, RNAseq allows the detection of molecular subtypes as different types of cancers can have varying gene expression profiles. For example, breast cancer alone has different subtypes such as triple-negative, HER2-positive and ER-positive. By identifying the molecular subtypes, this can guide personalised medicine to treat cancers (1). 

**Understanding RNAseq data using Data Science and Machine Learning**

There are many critical steps involved in the analysis of RNAseq data. The first step is preprocessing the data before analysis. This step requires quality control, filtering and normalization of the data to eliminate noise and correct for biases. Data science tools such as FastQC examine the quality of raw reads by checking for issues such as low-quality bases, adapter contamination, and GC content bias. In addition, RNA-seq data is high-dimensional, meaning the dataset has a large number of features (thousands of genes across several samples) which can be difficult to analyse computationally. To reduce this dimensionality, Principal Component Analysis (PCA) or t-distributed Stochastic Neighbour Embedding (t-SNE) is applied to make it simpler to analyse the data while maintaining critical biological signals. The main objective of RNAseq analysis is to detect differential genes between conditions, i.e. tumour vs non-tumour. Applying statistical tools can be used to make these distinctions and see differences in expression levels (2). 

**Conclusion**

In conclusion, RNAseq contributes to an important role in progressing our understanding of tumour biology by detecting molecular drivers of cancer to allow the advancement of personalised treatments. RNAseq technology showcases a detailed display of the transcriptome that is critical for understanding the underlying complexities of cancer and improving the outcome of cancer patients. By incorporating RNAseq datasets with other omics data i.e. proteomics, alongside data science and machine learning tools, researchers can establish complete molecular profiles of tumours. 

\
\


**References**

1. Camps, J. _et al._ (2023) _Supplementary data from meta-analysis of human cancer single-cell RNA-seq datasets using the IMMUCAN database_. doi:10.1158/0008-5472.22432629.v1. 

2. Andrews, T.S. _et al._ (2020) ‘Tutorial: Guidelines for the computational analysis of single-cell RNA sequencing data’, _Nature Protocols_, 16(1), pp. 1–9. doi:10.1038/s41596-020-00409-w. 

\


<!--EndFragment-->
