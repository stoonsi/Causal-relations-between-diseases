# Causal relations between diseases
# This repository is for our paper: Causal relationships between diseases mined from the literature improve the use of polygenic risk scores
The paper discusses the creation of a Directed Acyclic Graph for causal relations between diseases mapped to ICD10 identifiers.

- The main DAG with various metrics included can be found in:
  - data/DDC_DAG.tsv
- The used dictionary of ICD10 names can be found in:
  - data/disease_dict.json
- The expert curated data that was used for evalution can be found in:
  - data/positives.tsv for curated positive relations
  - data/negatives.tsv for curated negative relations
