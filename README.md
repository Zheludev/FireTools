# FireTools
a parent repo for tools written by I.N.Z during their tenure at the Fire Lab


# Tools:

## [KrakenGrafter](https://github.com/Zheludev/KrakenGrafter)

for adding new sequences to Kraken2 databases (see repo)

## [Bracken2OTU](https://github.com/Zheludev/Bracken2OTU)

for merging outputs from Bracken into OTU tables with the option to sum subsets of the outputs (see repo)

## [FASTACleanUp](https://github.com/Zheludev/VNom/blob/main/dependencies/FASTACleanUp.py)

for sorting and length-based filtering of FASTA formatted sequences, also produces single-line output of an input FASTA - good for CLI work

## [MSAcleaner](https://github.com/Zheludev/MSAcleaner)

a draft script for omitting sequences from MSAs that contribute to weakly supported insertions (given a reference set of sequences)

## [SeqDoubler](https://github.com/Zheludev/SeqDoubler)

a simple script that doubles input FASTA formatted sequences (must be single-line)

## [SeqDoubler](https://github.com/Zheludev/SeqMatchCheck)

a simple bash script based on [bioawk](https://github.com/lh3/bioawk) that checks if two .fastx files have exactly matching sequences in the same positions - used to check if [fastp](https://github.com/OpenGene/fastp) made a duplication error
