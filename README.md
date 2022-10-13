file link https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE212740
file name GSM6544281_2001_Pre.tar.gz this file contanins matrix.mtx, features.tsv and barcode.tsv that described feature-barcode matrices as outpute 
this output pipeline is read by Read10X() function
steps 
  Attaching package: 'dplyr'
  The following objects are masked from 'package:stats':filter, lag
  The following objects are masked from 'package:base':intersect, setdiff, setequal, union
  Attaching library SeuratObject ,patchwork,dplyr
  Load the PBMC dataset
  Initialize the Seurat object with the raw (non-normalized data).
  Warning: Feature names cannot have underscores ('_'), replacing with dashes
   An object of class Seurat 
  13714 features across 2700 samples within 1 assay 
  Active assay: RNA (13714 features, 0 variable features)
  50 x 10 sparse Matrix of class "dgCMatrix"
  [[ suppressing 10 column names 'AAACATACAACCAC-1', 'AAACATTGAGCTAC-1', 'AAACATTGATCAGC-1' ... ]]
  Visualize QC metrics as a violin plot
  FeatureScatter is typically used to visualize feature-feature relationships, but can be used
 for anything calculated by the object, i.e. columns in object metadata, PC scores etc.
 Identify the 10 most highly variable genes
 plot variable features with and without labels
 When using repel, set xnudge and ynudge to 0 for optimal results
 Warning: Transformation introduced infinite values in continuous x-axis
Centering and scaling data matrix
Computing nearest neighbor graph
Computing SNN
Calculating clusters
Registered S3 method overwritten by 'cli':
method     from         
print.boxx spatstat.geom
