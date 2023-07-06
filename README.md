# Master Bioinformatics
This repository is used for mastering processing techniques in Bioinformatics 

## :white_check_mark: Setup
- Create Python environment\
`conda create -n env_name python=3.10`\
`conda activate env_name`
- Install required packages for production\
`pip install -r requirements.txt`\
`pip install -r requirements-dev.txt`
- Install required packages for developement\
- Note: Some required packages: e.g. pysam or HTSeq, etc, can only be installed in Linux-like systems


## :white_check_mark: Datasets
- Create a new sub-folder: 'datasets' for storing the datasets
- Download the datasets from the links provided in the notebooks
- At the beginning of each notebook file, there is cmd to download the dataset with 'wget', be sure to run them in terminal Linux-like systems
- Copy the download datasets and paste into the folder 'datasets'

## :white_check_mark: Source code structure
- Next-Generation Sequencing
  - A1_Accessing_Databases.ipynb
  - A2_Basic_Sequence_Processing.ipynb
  - A3_Working_with_FASTQ.ipynb
  - A4_Working_with_BAM.ipynb
  - A5_Working_with_VCF.ipynb
  - A6_Filtering_SNPs.ipynb
  - A7_Processing_BED_with_HTSeq.ipynb
- Working with Genomes
  - B1_Reference_Genome.ipynb
  - B2_Low_Quality.ipynb
  - B3_Annotations.ipynb
  - B4_Getting_Gene.ipynb
  - B5_Orthology.ipynb
  - B6_Gene_Ontology.ipynb
- Processing Big Genomics Datasets
  - C1_HDF5.ipynb
  - C2_Dask.ipynb
  - C3_Parquet.ipynb
  - C4_Spark.ipynb
  - C5_Cython_Numba.ipynb

  ## :white_check_mark: References
  - [Bioinformatics with Python Cookbook - Third Edition](https://www.packtpub.com/product/bioinformatics-with-python-cookbook-third-edition/9781803236421#_ga=2.160515455.376582807.1688459579-309396850.1672914058). [Full source-code](https://github.com/PacktPublishing/Bioinformatics-with-Python-Cookbook-Second-Edition)
  - [Machine Learning in Biotechnology and Life Sciences](https://www.packtpub.com/product/machine-learning-in-biotechnology-and-life-sciences/9781801811910#_ga=2.166266364.376582807.1688459579-309396850.1672914058). [Full source-code](https://github.com/PacktPublishing/Machine-Learning-in-Biotechnology-and-Life-Sciences)

