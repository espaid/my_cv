Cancer Gene Expression data Analysis

Introduction

In this report, I present the results of my analysis on a cancer gene expression dataset given as a
task to me from Merlab. The objective of the analysis was to identify key genes associated with
tumour and normal samples which are TCGA patients Ids using clustering and differential
expression analysis. The analysis was performed on the dataset named "expression_data" which
contains gene expression values for different features (genes) across multiple samples from file
“TCGA-BRCA.htseq_counts_gene_name.tsv”.

Methodology

The analysis involved several key steps:

Data Preprocessing

I initially subsetted the samples that were present in both the "expression_data" and "sample_info"
datasets taken from file “TCGA-BRCA.pheno.tsv”. This ensured that we were working with consistent
samples throughout the analysis.

Differential Expression Analysis

I compared the mean gene expression levels between tumor and normal samples. By calculating the
absolute difference in mean expression, I identified the top 100 features (genes) that showed the
highest differential expression between the two sample types.

Clustering

I performed clustering analysis using the selected top features. The clustering was based on the
expression patterns of the genes across samples. Then I generated a heatmap to visualise the
clustering results, providing insights into the underlying patterns and relationships between the
samples.

Results

The clustering analysis revealed distinct clusters of samples based on the expression patterns of the
top genes. The heatmap depicted in Fig 1.0 demonstrates the clustering results, with samples
grouped based on their similarities in gene expression profiles.
The analysis identified several key genes that were highly associated with tumor and normal
samples. The top genes, as listed in Table 1, exhibited significant differential expression between
tumor and normal samples.

Top 5 Genes and Their Differential Expression Values:

Sr. Gene (feature) ID
1 AQP5
2 MMP11
3 S100A9
4 CLCA2
5 MAB21L4

Conclusion

In conclusion, our analysis of cancer gene expression data successfully identified key genes with
tumor and normal samples. The clustering analysis and heatmap revealed distinct groups of
samples based on gene expression patterns, highlighting the heterogeneity among different cancer
subtypes. The top genes identified through differential expression analysis provided insights into the
molecular mechanisms underlying cancer development. Follow-up experiments and functional
studies can provide deeper insights into the roles of these genes in cancer progression and
potentially lead to the development of targeted therapies.
References
No references
