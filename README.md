# download-features
This is a program to download features from BV-BRC website through an API when patrid ID is provided

# To retrieve genome data in FASTA format using the P3 command line, you can follow these steps:

Open a terminal or command prompt on your computer.
Log in to the PATRIC server using the p3-login command and your PATRIC username and password.
Use the p3-genome-fasta command to retrieve the genome data in FASTA format. The basic syntax of the command is:

p3-genome-fasta [options] genome_id > output_file.fasta



Replace "genome_id" with the ID of the genome you want to retrieve and "output_file.fasta" with the name you want to give the output file.

For example, to retrieve the genome data for the Salmonella str. 590.11958 genome in FASTA format and save it to a file called "590_11958.fasta", you would run the following command:

p3-genome-fasta 590.11958 > 590_11958.fasta


# To retrieve protein features data in FASTA format using the P3 command line, you can follow these steps:


P3-genome-fasta –feature genome_id > output_file.fasta


For example, to retrieve the genome data for the Salmonella str. 590.11958 genome in FASTA format and save it to a file called "590_11958.fasta", you would run the following command:

p3-genome-fasta –feature 590.11958 > 590_11958.fasta


