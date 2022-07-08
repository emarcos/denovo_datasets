# denovo_datasets
Datasets collected for de novo designed proteins

Designs from previous studies were analyzed based on several descriptors related to structure and surface properties. The structures of the designs were predicted with AlphaFold2 and RoseTTAFold. The local sequence-structure compatibility was analyzed by fragment quality. Other descriptors specific for each dataset were calculated.

**Contents:**
* **binder mimetics of the Botulinum neurotoxin (BoNT)**
  Designs were collected from Silva et al. (2016) doi: 10.1038/nature23912
  Binding interfaces were analyzed with Rosetta.
* **monomers in a variety folds (Monomer)**
  Designed sequences were obtained from several studies, as referenced in the monomer.csv file. 
  Homodimer predictions were generated with ColabFold, and the interfaces were analyzed with Rosetta.
  Soluble expression scores were predicted based on the amino acid sequence with Soluprot and Graphsol.
  The top-pLDDT AlphaFold model of each sequence was used to calculate structure-based descriptors, including those related to surface hydrophobicity.
  
Classification models were generated based on the calculated descriptors.
