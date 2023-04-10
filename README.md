# CTXM_epistasis
Datasets and custom script for processing data published in Judge et al. 

# Data analysis pipeline and datasets
The included data analysis pipeline is designed to process paired end Illumina sequencing and search for single codon variations in a designated DNA sequence window, also known as deep mutational scanning (DMS).
The "sample_count_data" includes count files for two double mutant libraries before and after selection, out of the 136 double position libraries processed, as a sample dataset for replicating this process.
The "fitness_data" folder documents includes count information, calculated fitness values, and sigma values for each double mutant. This processed data was the input for epistasis determination using the DMS2structure program in R (https://github.com/lehner-lab/DMS2structure). The output of the DMS2structure program can be found in the subfolder "DMS2_processed_data".

# Required software
Scripts are executable in Python 3. Files uploaded here were created and executed in Jupyter notebook using a Python 3 kernel.

# Required Python packages for data processing
Biopython  
Seq.IO  
re  
csv  
math  
pandas  

# Required Python packages for data visualization
pandas  
csv  
networkx  
matplotlib  
imageio  
numpy  
seaborn  
