This repository includes all of the bash scripts for utilizing QIIME2 in the ARC supercomputing cluster to process raw 16S rRNA gene amplicon sequencing files. 

These data were used to create figures X, Y, Z.

All file names were left intact but file paths were replaced with "/yourfilepath/"

Start by uploading all of your raw sequences (fastq files), manifest file, and metadata file to the folder that you will use throughout the workflow.

Use the bash scripts in this order:
1. manifest
2. qaqc
3. dada2 (denoising)
4. classify
5. phylogeny
6. export
7. rename
