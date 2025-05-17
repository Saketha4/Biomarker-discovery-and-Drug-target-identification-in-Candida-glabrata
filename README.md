# Biomarker discovery and Drug target identification in Candida glabrata

 Candida glabrata is an opportunistic yeast that poses a significant threat to immunocompromised individuals, largely due to its increasing resistance to antifungal treatments. Unlike other Candida species,  C. glabrata exhibits a high degree of intrinsic resistance to azoles and echinocandins, and its virulence is often compounded by its ability to form biofilms and evade immune responses. Therefore, identifying unique biomarkers and effective drug targets is crucial for developing novel therapeutic strategies.
 
 This project presents an integrative approach combining computational techniques to discover biomarkers and identify novel drug targets for Candida glabrata. The methodology utilizes genome-scale metabolic models (GEMM), BLASTp, AlphaFold, DALI, and molecular docking to uncover potential therapeutic targets that are unique to C. glabrata, with minimal off-target effects on humans

# Project Goals#

 • __Biomarker Discovery__: Identify proteins unique to C. glabrata that can be used as diagnostic biomarkers for infection detection. \
 • __Drug Target Identification__: Identify novel drug targets that could be exploited to treat C. glabrata infections, with a focus on targets that are essential for fungal survival and not present in human cells.\
 • __In Silico Validation__: Use computational techniques to validate identified targets through structure prediction, drug-likeness screening, and molecular docking studies.
 
# **Methodology**

## **Genome-Scale Metabolic Model (GEMM)**
The GEMM for Candida glabrata is constructed using publicly available genomic and transcriptomic data. The metabolic network reconstruction is facilitated by tools such as the COBRA Toolbox, allowing for the exploration of metabolic pathways critical to pathogenicity and drug resistance.
* [CG_GSMM](https://1drv.ms/x/c/82e11bf00f8ea8cf/EcuVGumvd4VJnTXWpR-F0m0B4oxQQlK9FLs8vF2GGozDkQ?e=LOarwH)

 Pathway Analysis: Metabolic pathways are analyzed to identify key processes contributing to virulence and potential biomarkers.

##  **Identification of Unique Proteins using BLASTp**
Proteome Comparison:
BLASTp is used to compare the Candida glabrata proteome against human proteins. A comprehensive database is prepared for comparison. BLASTp parameters (e.g., e-value threshold, scoring matrix) are set appropriately to identify unique proteins.
Candidate Biomarkers: The results are filtered to select proteins unique to Candida glabrata without homologs in humans, reducing the risk of off-target effects.

## **Structure Prediction using AlphaFold**
AlphaFold Implementation:
AlphaFold is utilized to predict the 3D structures of the unique proteins identified through BLASTp. The protein sequences are prepared as input for AlphaFold.

## **Structure-Based Searches using DALI**
DALI Search:
Predicted protein structures are submitted to the DALI server to identify structurally similar proteins with known functions. The results are interpreted to uncover potential functional insights and conserved mechanisms that could inform target selection.

## **Molecular Docking**
Docking Setup:
Molecular docking studies are conducted to evaluate interactions between the unique proteins and potential small molecule inhibitors. Software such as AutoDock Vina is used, with parameters set for binding site identification and docking simulations.

#  Results
 • __Unique Proteins__: A list of C. glabrata proteins that are absent in humans, which could serve as novel biomarkers for diagnosis or therapeutic intervention.
 • __3D Structures__: High-confidence structural predictions for identified proteins that can inform drug design.
 • __Docking Scores__: Insights into the binding affinity of potential inhibitors to the target proteins.

 # Tools and Resources
 • BLASTp: For proteome comparison and identification of unique proteins.\
 • COBRA Toolbox / cobrapy: For genome-scale metabolic modeling and flux balance analysis.\
 • AlphaFold: For structure prediction of unique proteins.\
 • DALI: For structure-based functional inference.\
 • AutoDock Vina: For molecular docking studies

## Discussion

# Conclusion


##  References


## Appendices

