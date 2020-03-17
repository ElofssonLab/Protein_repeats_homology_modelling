# Protein_repeats_homology_modelling
For the homology modelling for of Proteins repeats, we used the HHpred software (Söding et al. 2005).
HHpred is available both as webserver and local installation (The use of both require a Modeller licence). 

Webserver
https://toolkit.tuebingen.mpg.de/tools/hhpred

Local installation:
Install HHpred following the instruction at 
https://github.com/soedinglab/hh-suite/tree/master/scripts/hhpred

Use it 
./hhpred.pl -i <infile> -o <outfile>
  where infile is a fasta or a3m file of the target repeat protein
