# C7-maize-syncom

This repository contains the code and associated files for the paper "Metabolic profiling and genome-scale modelling uncover mechanistic drivers of microbiome stability in synthetic maize root community".

There are 4 main folders: 
1. Datatsets 
   * protein fasta files (.faa) for the seven bacterial species; used to create the metabolic model with carveme
   * csv file for creating a community model with MICOM
   * csv files that contain metabolite and reaction info from BIGG
   * csv files that contain different media composition
2. Models, i.e. metabolic models as .xml files (1. after creation with carveme and 2. after curation, used for all analyses)
3. Reports, i.e. MEMOTE and MACAW reports to check model quality 
4. Scripts, i.e. Jupyter Notebooks that contain all analyses and simulations as well as a python file that contains all functions that are used in multiple notebooks
