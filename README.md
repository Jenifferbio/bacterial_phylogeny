# Bacterial Phylogenomic Analysis

## Objective  
Reconstruct phylogenetic trees from bacterial genomes to study evolutionary relationships.

## Tools Used 
- **Alignment**: MAFFT, MUSCLE
  
## Workflow  
1. **Data Preparation**: Download genomes from RefSeq (NCBI).  
2. **Alignment**: `mafft --auto input.fasta > aligned.fasta`  
3. **Tree Construction**: `raxmlHPC -s aligned.fasta -m GTRGAMMA -p 12345`  
4. **Visualization**: Scripts in

## Results  
- Phylogenetic tree highlighting .... clusters.  
- Bootstrap support values >90% for major clades. 
