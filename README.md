# EGFR-Ras-MAPK Bond Graph Model

The EGFR-Ras-MAPK signalling pathway consists of two major networks: 1. EGFR pathway, 2. MAPK cascade.

The bond graph model of the EGFR pathway along with the parameter estimation is available at :point_right: [EGFR pathway](https://github.com/Niloofar-Sh/EGFR_MAPK/tree/main/EGF)

The bond graph model of the MAPK cascade along with its dependencies is available in :point_right: [MAPK cascade](https://github.com/Niloofar-Sh/EGFR_MAPK/tree/main/MAPK%20cascade)

A third module was also modified out of the Brighman & Fell's model to account for some missing intermediate steps between the two major modules. We called it the Ras module and is available in :point_right: [Ras](https://github.com/Niloofar-Sh/EGFR_MAPK/tree/main/Ras)

To run the models you need to first install BondGraphTools, and then download and save the required ontologies as .csv files:

- OPB: https://bioportal.bioontology.org/ontologies/OPB
- GO: https://bioportal.bioontology.org/ontologies/GO

__Since the size of the stored ontologies exceeds the GitHub upload limit, the ontologies' .csv files are not uploaded here.__

The composed bond graph model of the EGFR-Ras-MAPK signalling pathway from its constitutive modules (EGFR & Ras & MAPK) is :point_right: [EGFR-Ras-MAPK](https://github.com/Niloofar-Sh/EGFR_MAPK/blob/main/EGF_Ras_MAPK.ipynb)

The modified annotated CellML models (or parameter sets) are stored in :point_right: [CellML files](https://github.com/Niloofar-Sh/EGFR_MAPK/tree/main/CellML%20files) 

The connectivity matrices for the modules are stored in :point_right: [Connectivity Matrices](https://github.com/Niloofar-Sh/EGFR_MAPK/tree/main/Connectivity%20Matrices)  

To observe the comparisons between our results and the original models and analyze the behaviour of the final composed model, go to :point_right: [Comparison](https://github.com/Niloofar-Sh/EGFR_MAPK/tree/main/Results_comparison) 

# How to run the models?

You need to install Python and pip install BondGraphTools from: [BondGraphTools GitHub repo](https://github.com/BondGraphTools/BondGraphTools)
