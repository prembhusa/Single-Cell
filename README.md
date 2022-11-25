Single cell analysis: In RNA-seq single cell analysis we analyse 10X Chromium single-cell RNA-seq profiles using R. This will include reading the count data into R, quality control, normalisation, dimensionality reduction, cell clustering and finding marker genes. The main part of the workflow uses the package SEURAT which is designed for QC, analysis, and exploration of single-cell RNA-seq data. Seurat aims to enable users to identify and interpret sources of heterogeneity from single-cell transcriptomic measurements, and to integrate diverse types of single-cell data.

File link: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE212740

CSV File: GSM6544281_2001_Pre.tar.gz
PROCEDURE:

Basic quality control and filtering.
Meta.data count for cell quality check.
Different plots of metadata feature to check correlation between them.The number above each plot is a Pearson correlation coefficient.
Variable Feature Plot to View variable features and their expression.
Violin plots of the selected metadata features.
DimHeatmap plot and Elbow plot: DimHeatMap helps to create heatmap of each principal component or several PCs at once. Basically, it draws a heatmap focusing on a principal component. Both cells and genes are sorted by their principal component scores. Allows for nice visualization of sources of heterogeneity in the dataset.
We can now do clustering. For visualization purposes, we also need to generate UMAP reduced dimensionality representation.
Dimplot: Graphs of dimplots are the output of a dimensional reduction technique on a 2D scatter plot where each point is a cell and it's positioned based on the cell embeddings determined by the reduction technique. By default, cells are colored by their identity class.
Finds markers (differentially expressed genes) for each of the identity classes in a dataset.
Visualize 'features' on a dimensional reduction plot.
Cell type annotation.
Result Interpretation: Some plots that generated based on dimension reduction technique, the Dimensionality Reduction is the process of reducing the number of features to the most relevant ones in simple terms.

PCA (Principal Component Analysis): Using DimHeatMap() we analysis by creating different heatmap,and genes are sorted by their score

UMAP (Uniform Manifold Approximation and Projection): UMAP is a nonlinear dimensionality reduction method, it is very effective for visualizing clusters or groups of data points and their relative proximities. Different clusters are also marked in the plot.
