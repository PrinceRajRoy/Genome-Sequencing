# Genome-Sequencing

A Gene Sequence Detector using Python which checks the gene sequences present in a Fasta file.
The GUI is basically made using Tkinter. It can be used by the user to upload the Fasta file.

The Fasta file here is "EcoliGeneSequences.txt"

Based on the file and certain conditions it gives the result as "Yes, It is a Fasta File" or "Not a Fasta file".

##The necessary conditions for a Fasta file are :-

1) Every Information Line Starts With A '>' Symbol.
2) The Gene Sequence only contains 4 characters which are 'A', 'T', 'G' and 'C'.
3) No blank line is present between infomation line and gene sequence.
4) Each information is contained in one single line and is not continued to the next line.

After the validation of the file, it is compared with another file "GeneDetails.txt" and the information corresponding from both of these files is stored in the database.

##Some Output Screenshots

![]()
