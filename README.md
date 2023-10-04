# Entity_Extraction_Hereditary_Disease_2023
This repository contains the data used in the manuscript named “A Combined Manual Annotation and Deep-learning Natural Language Processing Study on Accurate Entity Extraction in Hereditary Disease Related Biomedical Literature” submitted to Bioinformatics Advances.

## bern_data_092023
The folder named “bern_data_092023” contains the annotated PubMed abstracts in .json format between the year of 1978 and the year of 2019 (pubmed19n0001.json ~ pubmed19n1200.json) from DIMS Lab. These data were used to prepare Phase I dataset for modeling in the manuscript. in the If necessary, please contact DIMS Lab (https://dmis.korea.ac.kr/) for data access to pubmed19n0019.json~pubmed19n1200.json.  

## data
In the folder named”data”, there are two folders—PhaseI_data and PHaeII_data. There are train, dev and test datasets used in Phase I and Phase II of BERT modeling in the manuscript, respectively. 
The data in the folder--PhaseI_data correspond to the corpus in the folder named “bern_data_092023”.
The data in the folder—PhaseII_data correspond to our 400 annotated PubMed articles.
