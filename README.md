# Ra

Overlap-layout-consensus based DNA assembler of long uncorrected reads (short for Rapid Assembler).

## Description

Ra is as a fast and easy to use assembler for raw reads generated by third generation sequencing. It consists of [Minimap](https://github.com/lh3/minimap), [Rala](https://github.com/rvaser/rala) and [Racon](https://github.com/isovic/racon) as depicted on figure bellow.

Ra takes as input a single file containing raw reads in FASTQ format and outputs a set of contigs with high accuracy in FASTA format.

## Dependencies
1. Python 3+
2. g++4.8+
3. Zlib (sudo apt-get install zlib1g-dev)

## Installation
To install Ra run to following commands:

    git clone https://github.com/rvaser/ra.git ra
    cd ra/
    python ra.py --install

## Usage

Run Ra with the following command:

    python ra.py --data <reads file>

## Contact information

For additional information, help and bug reports please send an email to: robert.vaser@fer.hr.

## Acknowledgement

This work has been supported in part by Croatian Science Foundation under the project UIP-11-2013-7353.
