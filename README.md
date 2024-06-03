# ISIS
Codes and SI for In silico identification of switching nodes in metabolic networks, by F. Mairet

Preprint (bioRxiv)
https://doi.org/10.1101/2023.05.17.541195 


Each folder corresponds to a case-study of the paper. In each case, the analysis can be carried out by running the jupyter notebook (Switch_X.ipynb). 

Below is a description of the contents of each folder:

## E_coli_core
- Ecoli_core_Flux.xlsx: fluxes for different conditions (computed by the script)
- Ecoli_core_Metabolite.xlsx: metabolite scores (computed by the script)
- Switch_Ecoli_core.html: copy of the script (readable without jupyter notebook) 
- Switch_Ecoli_core.ipynb: script
- e_coli_core.xml: metabolic network (from Orth et al., 2010) 


## E_coli
- Ecoli_core_Flux.xlsx: fluxes for different conditions (computed by the script)
- Ecoli_core_Metabolite.xlsx: metabolite scores (computed by the script)
- Ligands1.xlsx: list of all the metabolites identified as ligand (from  Brunk et al., 2018)
- MetaboSwithLig.xlsx: list of the metabolites with their score and if they are identified as a ligand (computed by the script)
- Switch_Ecoli.html: copy of the script (readable without jupyter notebook) 
- Switch_Ecoli.ipynb: script
- iAF1260.xml: metabolic network (from Feist et al., 2007)  
- medium.xlsx: list of all the nutrient inputs (from Brunk et al., 2018)

## P_tricornutum
- FBA_Phaeo.xls: fluxes for the different conditions (from Kim et al., 2016)
- Phaeo_Metabolite.xlsx: metabolite scores (computed by the script)
- Switch_Phaeo.html: copy of the script (readable without jupyter notebook) 
- Switch_Phaeo.ipynb: script
- tpj.sbml: metabolic network (from Kim et al., 2016) 

## S_cerevisiae 
- S_cerevisiae _Flux.xlsx: fluxes for different conditions (computed by the script)
- S_cerevisiae _Metabolite.xlsx: metabolite scores (computed by the script)
- Switch_yeast.html: copy of the script (readable without jupyter notebook) 
- Switch_yeast.ipynb: script
- yeastGEM.xml: metabolic network (from  Herrgard et al., 2008)

## Robustness_E_coli_core
- Flux_samples_Aerobic.xlsx: fluxes for aerobic condition using sampling (computed by the script)
- Flux_samples_Anaerobic.xlsx: fluxes for anaerobic condition using sampling (computed by the script)
- Ecoli_core_Metabolite_Sampling.xlsx: metabolite scores (computed by the script)
- Switch_Ecoli_core_sampling.html: copy of the script (readable without jupyter notebook) 
- Switch_Ecoli_core_sampling.ipynb: script
- e_coli_core.xml: metabolic network (from Orth et al., 2010)

## Robustness_S_cerevisiae 
- Flux_sample_Gln.xlsx: fluxes for Gln input using sampling (computed by the script)
- Flux_sample_Ala.xlsx: fluxes for Ala input using sampling (computed by the script)
- Flux_sample_NH4.xlsx: fluxes for NH4 input using sampling (computed by the script)
- S_cerevisiae _Metabolite_sampling.xlsx: metabolite scores (computed by the script)
- Switch_yeast_sample.html: copy of the script (readable without jupyter notebook) 
- Switch_yeast_sample.ipynb: script
- yeastGEM.xml: metabolic network (from  Herrgard et al., 2008)
