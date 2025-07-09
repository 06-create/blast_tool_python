Python BLAST Tool using Biopython

This project uses **Biopython** to run a BLAST (Basic Local Alignment Search Tool) search on a DNA sequence and analyze the results.


Features
- Runs BLASTn (nucleotide BLAST) against the NCBI `nt` database
- Saves results in XML format
- Parses and displays top 5 matches (title, length, E-value)

Output
One of the top 5 Matches:
Title: gi|2852408356|emb|OZ040817.1| Escherichia coli isolate 30345_1#232 genome assembly, chromosome: 1
Length: 4945806
E-value: 1.25912e-14

 Files
- `blast_tool.ipynb`: Main Google Colab notebook
- `blast_result.xml`: Output file from NCBI

