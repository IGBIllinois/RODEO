# RODEO
This project is maintained by the Mitchell Research Lab at the University of Illinois at Urbana-Champaign. 

RODEO (Rapid ORF Description &amp; Evaluation Online) is an algorithm to help biosynthetic gene cluster (BGC) analysis, with an emphasis on ribosomal natural product (RiPP) discovery: http://www.ripprodeo.org

RODEO evaluates one or many genes, characterizing a gene neighborhood based on the presence of profile hidden Markov models (pHMMs). Because RiPP precursor peptides are small and often evade annotation in sequence databases, RODEO can also manually translate small ORFs (open reading frames). A combination of support vector machine (SVM) learning and motif analysis can be used to scan unannotated intergenic regions for RiPP precursors.

With RODEO, thousands of gene clusters can be annotated in a single analysis. We have used RODEO to survey the biosynthetic landscape of certain RiPPs, annotate sequence-similarity networks, annotate phylogenetic trees, decipher evolutionary relationships between enzymes & substrates, and track protein-protein co-occurrence. RODEO works on bacterial, archaeal, and fungal genomes.

For more information, see our publication in Nature Chemical Biology: http://www.nature.com/nchembio/journal/v13/n5/full/nchembio.2319.html
