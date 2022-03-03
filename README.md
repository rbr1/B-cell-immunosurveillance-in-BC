# B-cell-immunosurveillance-in-BC

This will identify pairs of sequences that are within 3 substitution differences. Example input file is provided in 
"Example_screen_pathogen-sequences.txt", where: 
  The first column contains *at least* the amino acid CDR3 sequences of the screen and reference sequences
  The second column defines whether the sequence is to be screened ("screen") or if it is a reference sequence ("reference")

An output file will be created defining all the matches within 3 substitution differences, detailing the number of differences 
between the reference and screen sequence, and the substring that matched between them. 

Users will need to edit lines 97 and 98 to direct to corret file location.
