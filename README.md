The first part of the assignment consists of writing a python script that maps a gene sequence into its corresponding protein sequence.\n",
    "<br>Three input files are needed for this assignment.",
    "\n",
    "1.\t**“gene_sequence.txt”:** the nucleotide sequence of the gene in question.\n",
    "2.\t**“exon_position.txt”:** contains the start and end positions of the exon regions. Each line holds the start and end positions of an exon region. To form the mRNA, only the exon regions (the coding parts) of the gene must be combined while replacing the letter T by the letter U.\n",
    "3.\t**“code.txt”:** contains the mapping of mRNA triplets to amino acids. The first column is the mRNA triplet, while the other columns represents the 1-letter symbol, a 3-letter name, and the full name of the corresponding amino acid. To create the protein, we replace the triplets of the mRNA strings by the corresponding 1-letter symbol.\n",
    
