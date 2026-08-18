# Comparative Bioinformatics Analysis of the Human ADRB2 Gene Across Mammalian Species
## Overview
This project investigates the structural characteristics and evolutionary relationships of the human ADRB2 (β2-adrenergic receptor) gene through comparative bioinformatics analysis.
The study compares ADRB2 protein sequences from multiple mammalian species using publicly available biological databases and bioinformatics tools.

## Objectives
- Retrieve the protein sequences from different selected mammals.
- Compare the protein sequences using BLASTP.
- Multiple sequence alignment by MAFFT or CLUSTAL OMEGA.
- Identify the conserved areas.
- Phylogeny tree for study of evolutionary relationships.
- To demonstrate a complete beginner-level bioinformatics sequence-analysis workflow.

## About ADRB2
ADRB2 Gene in Homo Sapiens encodes for **Beta-2 adrenergic receptor** i.e. a G- protein coupled receptor activated by epinephrine (adrenaline).
The beta-2 adrenergic receptor is involved in cellular responses to adrenaline and related catecholamines and plays an important role in processes such as:
  1. Smooth Muscle relaxation
  2. Regulation of airway function
  3. Cardiovascular responses
  4. Signal transduction
  5. G-protein-mediated cellular signalling
Works by interacting with Epinephrine or similar artificially made **Beta- 2 antagonist drugs** that mimics epinephrine to give relief from the muscle contraction especially in lungs and uterine muscle.
ADRB2 Gene is broadly used in pharmacology.
Because ADRB2 is conserved across different species, it provides a useful model for studying sequence conservation and evolutionary relationships.

## Tools Included
- NCBI
- UNIPROT
- BLAST
- MAFFT/CLUSTAL W
- MEGA

## Species Studied 

|       Scientific Names       |        Common names       |         Primary Accession        |
| --- | --- | --- |
| Homo sapiens | Human | P07550 |
| Mus musculus | Mouse | P18762 |
| Rattus norvegicus | Brown Rat | P10608 |
| Sus scrofa | Pig | Q28997 |
| Bos taurus | Bovine cow | Q28044 |


## Work Order
1. Retrieve the data from the databases.
2. Download the files in FASTA format.
3. Perform BLASTP analysis.
4. Conduct multiple sequence alignment.
5. Comparative analysis.
6. Build phylogenetic tree.
7. Conclusion

## Learning Outcomes
- Retrieval of sequences from different databases available.
- Similarity analysis.
- Multiple sequence alignment and identification of conserved regions.
- Evolutionary relationship.

## Methodology
### 1. Sequence Retrieval
The ADRB2 sequence was obtained from a public sequence database (UniProt).
Sequences corresponding to ADRB2 from the selected organism were collected for the comparative analysis.
These sequences are saved in FASTA format.

 - A FASTA format file generally contains the sequence ID and sequence identifier.

### 2. Blast Analysis
Basic Local Alignment Search Tool is basically used to identify the similar sequences of the query sequences and also identifies the similarity by comparing the query sequence against sequences present in a selected database.

Some analyzed parameters are:
- % Identity
-The percentage of the positions in aligned region that are identical between the query and reference sequence.
-For example:
-Query: ATGCGCT
-Reference: ATCCCCT
-Therefore, 5 out of 7 positions are identical, so the % identity would be 71.428 %.
-A higher percentage identity generally indicates greater sequence similarity.


- Query Coverage
- 
