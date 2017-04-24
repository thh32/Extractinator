# Extractinator
Uses GFF files to identify regions of interest within a sequence file and produce a separate file of only these extracted regions.


Extractinator requires both the argparse and HTSeq modules of Python to be installed.

To use Extractinator;

`Extractinator.py -i Input.fasta -fasta -g Input.gff -o Output.fasta`

This will run Extractinator and produce an output file with the CDS regions identified by the GFF. 

Alternatively the `-t` command can be used to identify another region within the GFF which is wanted such as `-t intron` or `-t exon`.
