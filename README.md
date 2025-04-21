# Comparatice Genomics Pipeline

## Function
Full Pipeline analysis from a Single Gene/Protein Sequence. (Optimized for High Accuracy/Quality Results)

Options:

1 - Full Auto Analysis (Single Protein)

2 - BLAST + MSA + PhyTree (Single Protein)

3 - Cut + MSA + Trim + PhyTree (List Proteins)

## Full Auto Analysis
1. Provide Original Sequence (Or Acession ID)
2. BLAST + MSA + Trim + PhyTree
3. Additional Analysis Tools
   3.1 Protein Annotations
      3.1.1 Protein Family (Pfam - ebi)
      3.1.2 Protein Functional Analysis ([EBI](https://www.ebi.ac.uk/jdispatcher/pfa)) (InterProScan,PfamScan,HMMER3 hmmscan,Phobius,Pratt,RADAR)
   3.2 Sequence Statistics
   

## Full Roadmap
1. Download Original Gene/Protein Sequence
2. Multiple Database Fech (NCBI | UniProt | EBI | PDB)
3. Sequence Translation (Transeq | Sixpack | Backtranseq | Backtranambig)
4. Sequence Similarity Search (NCBI BLAST | PSI-BLAST | FASTA | SSEARCH | PSI-Search | PSI-Search2 | GGSEARCH | GLSEARCH | FASTM/S/F | HMMER3 phmmer | HMMER3 nhmmer )
5. Multiple Sequence Alignment (Clustal Omega | Cons | Kalign | MAFFT | MUSCLE | MUSCLE 5 | MView | T-Coffee | WebPRANK)
6. Phylogeny (Simple Phylogeny | IQTree)
7. Sequence Statistics (Pepinfo | Pepstats | Pepwindow | SAPS | Cpgplot | Newcpgreport | Isochore | Dotmatcher | Dotpath | Dottup | Polydot)

## ToDo Functions/Classes
0. Install nedded programs (Linux/Windows)
1. Database Protien sequence Fetch (|Sigle/List Proteins|)
   1.1 Allow IDs from multiple Databases
   1.2 Cut sequence (Optional)
2. Create Fasta file with Personalized Headers (|List Proteins|)
4. Local Mafft MSA (Local + Global) (High Accuracy)
5. Local IQTree (High Accuracy)
6. Sequence Similarity Search (|Single protein|)
   6.1 NCBI BLAST
   6.2 Additional Searches
   6.3 Remove duplicated Results
   6.4 Create Results Fasta
8. Sequence Statistics (|Single protein|)
   7.1 Use EBI API
   7.2 Create Results File
9. Protein Functional Analysis
   7.1 Use EBI API
   7.2 Request InterProScan, PfamScan, HMMER3 hmmscan, Phobius, Pratt, RADAR
   7.3 Create Results File
10. Final Summary
   9.1 Simple summary off all information
   9.2 Maybe HTML file (Easier visualization)
11. Evolutionary Tree
   11.1 Fetch "Sequence Similarity Search" Species
   11.2 Fetch Conserved Species Genes (SILVA |
   11.3 Create species FASTA file
   11.4 IQTree to create Species Tree **
   **Is MSA required for Species Trees?
12. UI
   12.1 Run Requests
   12.2 Vizualize Results
   12.3 Follow Progression
