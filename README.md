# C7-maize-syncom

This repository contains the code and associated files for the paper "Metabolic profiling and genome-scale modelling uncover mechanistic drivers of microbiome stability in synthetic maize root community".

There are 4 main folders: 
1. Datatsets 
   * protein fasta files (.faa) for the seven bacterial species; used to create the metabolic model with carveme
   * csv file for creating a community model with MICOM
   * BIGG: csv files that contain metabolite and reaction info from BIGG
   * Duplicate_Investigation: csv files for curation duplicated metabolites and reactions
   * In-silico_data: in silico results from jupyter notebooks, prepared as csv files for easier figure creation
   * In-vitro_data: in vitro results from the supplementary Tables, prepared as csv files to generate figures
   * Medium:csv files that contain different media composition
2. Models, i.e. metabolic models as .xml files (1. after creation with carveme and 2. after curation, used for all analyses)
3. Reports, i.e. MEMOTE and MACAW reports to check model quality 
4. Scripts, i.e. Jupyter Notebooks that contain all analyses and simulations as well as a python file that contains functions that are used in multiple notebooks
