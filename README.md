# epilepsy-autism-PPI-network

In order to reproduce the results of the paper, run the Jupyter Notebook **epilepsy-autism.ipynb**.  The notebook is divided into different sections and has comments to help you produce the results.  

You will need to download **9606.protein.links.v11.0.txt** from STRING version 11 (https://string-db.org/cgi/download.pl?sessionId=GGXABQ8MKE5v&species_text=Homo+sapiens). This file contains all the protein-protein interactions. If you want to filter by the type of evidence for the protein-protein interactions, you will need to download **9606.protein.links.detailed.v11.0.txt** from the same link.  

You will need to download **9606.protein.info.v11.0.txt** from STRING version 11 (https://string-db.org/cgi/download.pl?sessionId=GGXABQ8MKE5v&species_text=Homo+sapiens). The file contains information to link the protein-protein interactions with their protein/gene names.

**environment.yml** is the Conda environment file that you can use to install all the dependencies for the code. 

The **figures** directory contains the figures outputted from the code (i.e. **epilepsy-autism.ipynb**), which are used in the paper.  

The **modules_DAVID** directory contains the biological process, molecular function, and cellular component gene ontology (GO) terms, from retrieved using DAVID (https://david.ncifcrf.gov/summary.jsp).  

The **output** directory contains files outputted from the code.  

**SFARI-Gene_genes_01-03-2020release_01-05-2020export.csv** contains the list of autism-associated genes retrieved from SFARI (https://gene.sfari.org/) on January 5, 2020. The gene list was last updated in SFARI on January 3, 2020.

**epilepsy_genes_wang_2017.csv** contains the list of epilepsy-associated genes from Wang et al. (2017) (https://www.sciencedirect.com/science/article/pii/S1059131116302989). 

**DE_genes.csv** contains a list of genes that are differentially expressed in brain tissue.  

**disease_genes.csv** contains a list of genes associated with schizophrenia, bipolar disorder, and intellectual disability, as well as excitatory postsynaptic density (ePSD) and inhibitory postsynaptic density (iPSD) proteins. These gene lists were retrieved from Wang et al. (2018) (https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5802446/).

**gene_info_all_genes.tsv** has a list of all the genes in the epilepsy-autism PPI network, which module they are in, in the epilepsy-autism PPI network, and whether they are an epilepsy gene ("e"), autism gene ("a"), or common gene ("c") that is associated with both epilepsy and autism.

**gene_info_k_17_with_modules.tsv** has a list of all the k-core genes (k=17) in the epilepsy-autism PPI network, which module they are in, in the k-core, and whether they are an epilepsy gene ("e"), autism gene ("a"), or common gene ("c") that is associated with both epilepsy and autism.

**WES_analysis.ipynb** has the code used for the whole-exome sequencing (WES) analysis that produced supplementary figure 2.

**WES_EPI_gene_burden_AC_1_Epi25_Collaborative_2019.csv** has the WES gene list for epilepsy.

**WES_autism_Satterstrom_2020.csv** has the WES gene list for autism.

The supplemental tables from the paper can be found in **Supp_tables_20200509.xlsx**.
