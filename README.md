# SeqSearch

SeqSeach is a tool for direct download of nucleotide and amino acid sequences in FASTA format from the public database "GenBank".
Available for Windows and GNU Linux.


INSTRUCTIONS

1. Download the correct version (32 or 64-bits) according to your OS.


2. Open the 'SeqSearch.exe' file inside the 'source' folder or create a shortcut to the Desktop;


3. Select the tab "Nucleotide" or "Protein". 
3.1 Nucleotide
-Type the taxon (ex: homo sapiens, arabidopsis thaliana, escherichia coli, etc.) or a related term (ex: human);
*For viruses: it is preferable to enter the entire name (ex: human papillomavirus, ebola virus, white spot syndrome virus, etc.)*
-If you are searching for a specific gene, for example, you have to type its name in the second input (ex: E1 ORF, ORF75, insulin, etc.);
-Check "Complete genome" when searching for entire genomes only OR "Complete cds" when searching for specific sequences (ex: genes and ORFs);
-In order to help you filtering the results, a size range may be defined. Enter an entire number for both inputs (if a Min value was typed, a Max value is required). They'll correspond to the total number of base pairs in a sequence.
Ex: Min value = 1000 --> only sequences with at least 1,000 base pairs will be downloaded;
    Max value = 10000 --> sequeces with up to 10 kb will be downloaded;
-Press "DOWNLOAD" and wait.

**************************************************************************************************************************************
Specific nucleotide sequences (ORFs and gene) may be difficult to find due to the lack of standardization of annotations in GenBank.
Setting a size range may facilitate the search and avoid downloading large undesirable sequences.
**************************************************************************************************************************************

3.2 Protein
-Type the taxon (ex: homo sapiens, arabidopsis thaliana, escherichia coli, etc.) or a related term (ex: human);
*For viruses: it is preferable to enter the entire name (ex: human papillomavirus, ebola virus, white spot syndrome virus, etc.)*
-If you are searching for a specific protein, you have to type its name in the second input (ex: E1 protein, insulin, myoglobin, etc.);
-Check "Remove partial sequences" if you want only complete amino acid sequences;
-In order to help you filtering the results, a size range may be defined. Enter an entire number for both inputs (if a Min value was typed, a Max value is required). They'll correspond to the total number of base pairs in a sequence.
Ex: Min value = 100 --> only sequences with at least 100 amino acids will be downloaded;
    Max value = 1000 --> sequeces with up to 1,000 aa will be downloaded;
-Press "DOWNLOAD" and wait.

3.3 Multiple Alignment
-After downloading, you may align the sequences using MUSCLE, MAFFT or Clustal Omega algorithms. 

************************************************************************************
For large sequence sets, an online tool is preferable. Use one of the links below:
http://www.ebi.ac.uk/Tools/msa/muscle/
http://www.ebi.ac.uk/Tools/msa/clustalo/
http://mafft.cbrc.jp/alignment/server/
************************************************************************************

4. The sequences downloaded remain saved inside the 'Fasta' folder, 
   but you can use the 'Save As' option in your text reader to save them anywhere;


Enjoy it!
