# EGFR_MAPK

The Ras/MAPK signalling pathway consists of two major networks: 1. EGFR pathway, 2. MAPK cascade.

The bond graph model of the EGFR pathway along with the parameter estimation is available at :point_right: [EGF][https://github.com/Niloofar-Sh/EGFR_MAPK/tree/main/EGF]

The bond graph model of the MAPK cascade along with its dependencies is available in :point_right: EGFR_MAPK/MAPK cascade.

To run the models you need to first install BondGraphTools, and then download and save the required ontologies as .csv files:

- CHEBI: https://bioportal.bioontology.org/ontologies/CHEBI
- FMA: https://bioportal.bioontology.org/ontologies/FMA
- OPB: https://bioportal.bioontology.org/ontologies/OPB
- GO: https://bioportal.bioontology.org/ontologies/GO

__Since the size of the stored ontologies exceeds the GitHub upload limit, the ontologies' .csv files are not uploaded here.__

The composed bond graph model of the EGFR-Ras-MAPK signalling pathway from its constitutive modules (EGFR & MAPK) is :point_right: EGFR_MAPK/MAPK_EGF_New.ipynb

The original annotated CellML models (or parameter sets) are stored in :point_right: EGFR_MAPK/CellML files

The connectivity matrices for the modules are stored in :point_right: EGFR_MAPK/Connectivity Matrices

To observe the comparisons between our results and the original models and analyze the behaviour of the final composed model, go to :point_right: EGFR_MAPK/Results_comparison/new_Comparison.ipynb
