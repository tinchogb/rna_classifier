# rna_classifier
Drop in your sequence and see what type of RNA is. The RNA type classifier is a Neural Network model trained with CoDNaS-RNA conformers information.

## Data sources

### CoDNaS-RNA
- Website: [CoDNaS-RNA](http://ufq.unq.edu.ar/codnasrna/)
- Release: 2024-08
- Description: Minimal redundant dataset of RNA sequences with SO annotations from RNAcentral.
- Filepath: [2025-08_cdrna_sequences.tsv.gz](./data/2025-08_cdrna_sequences.tsv.gz)


### Sequence Ontology
- Website: [Sequence Ontology](http://www.sequenceontology.org/)
- Repository: [The Sequence Ontology - SO-Ontologies](https://github.com/The-Sequence-Ontology/SO-Ontologies)
- Official source: [Open Biological and Biomedical Ontology Foundry - SO](https://obofoundry.org/ontology/so.html)
    | Format |   File   | Git Commit
    |--------|----------|------------
    | OBO    | [so.obo ](https://purl.obolibrary.org/obo/so.obo) | [9d2c7c1](https://github.com/The-Sequence-Ontology/SO-Ontologies/commit/9d2c7c11aa2ae113627134af2fd9cf71496192f6)
    | OWL    | [so.owl](https://purl.obolibrary.org/obo/so.owl) | [9d2c7c1](https://github.com/The-Sequence-Ontology/SO-Ontologies/commit/9d2c7c11aa2ae113627134af2fd9cf71496192f6)
- Filepaths:
  - [so.obo](./data/so.obo)
  - [so.owl](./data/so.owl)
