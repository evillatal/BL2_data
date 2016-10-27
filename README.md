# BL2_data
This file describe the data in this repository, used in the paper "Machine learning based detection of causal gene-gene interactions from observational gene expression time series data" by Edwin Villanueva, Soledad Espezua, Franziska Taruttis, Elisabeth Hand, Dieter Kube, Rainer Spang and Andre C.P.L.F. de Carvalho, submitted to BMC Bioinformatics. 

The repository have four folders: Raw, Di, Dc and Tt, each containing data of the set of features relative to the folder´s name. Inside each folder there are seven CSV files, each one relative to a different inhibitor (identified by the name of the file). The files have the following columns:
 - CauseGene: Name of the cause gene  
 - EffectGene: Name of the effect gene
 - Replicate: Number of the replicate
 - Treatment: Type of cell stimulation (BCR or CD40)
 - Pvalue: The adjusted p-value of differential expression comparing gene expression levels prior and after the inhibition experiment. This information is used to determine the label of the instance (causal or not-causal)
 - Remaining columns: the features relative to the current Feature set (folder's name).

