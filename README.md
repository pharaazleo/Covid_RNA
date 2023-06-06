# Nucleic Acid Sequence Manipulator

## Introduction
This Python program allows you to manipulate nucleic acid sequences, specifically DNA and RNA. It provides functionality to construct reverse, complement, and reverse-complement sequences. Additionally, it can read a file containing a long DNA sequence, enabling you to work with complete genomes of the novel coronavirus.

## Overview
RNA (ribonucleic acid) and DNA (deoxyribonucleic acid) are two types of nucleic acids that play essential roles in storing and transmitting genetic information. The building blocks of RNA and DNA are nucleotides, which consist of a sugar molecule (ribose in RNA and deoxyribose in DNA), a phosphate group, and a nitrogenous base.

The nitrogenous bases in RNA and DNA are responsible for base pairing, which forms the complementary bonds between nucleic acid strands. Base pairing is crucial for replication, transcription, and translation processes in genetic information flow.

## RNA Base Pairing
In RNA, there are four types of nitrogenous bases: adenine (A), cytosine (C), guanine (G), and uracil (U). The base pairing rules for RNA are as follows:
- Adenine (A) pairs with uracil (U) using two hydrogen bonds.
- Cytosine (C) pairs with guanine (G) using three hydrogen bonds.

The RNA base pairs form the foundation for the secondary structure of RNA molecules, including the formation of hairpin loops, stem-loops, and other intricate folding patterns.

## DNA Base Pairing
In DNA, there are also four types of nitrogenous bases: adenine (A), cytosine (C), guanine (G), and thymine (T). The base pairing rules for DNA are as follows:
- Adenine (A) pairs with thymine (T) using two hydrogen bonds.
- Cytosine (C) pairs with guanine (G) using three hydrogen bonds.

The DNA base pairs are responsible for the double helix structure of DNA, where two strands of DNA wind around each other in an antiparallel fashion. The complementary base pairing allows for accurate DNA replication and ensures the faithful transmission of genetic information during cell division.

## Importance of Base Pairing
The novel coronavirus is an RNA virus, which means its genetic material is composed of a single-stranded RNA molecule. However, in the provided data by NCBI, we observe a DNA sequence. We can differentiate between RNA and DNA based on the presence of a specific nucleotide called thymine. Thymine is exclusively found in DNA sequences and does not occur naturally in RNA. When biologists sequence the genome of a virus, they employ an enzyme called reverse transcriptase. This enzyme converts the viral RNA into a complementary DNA sequence, known as cDNA.

To retrieve the genome of the virus accurately, we need to obtain the complementary DNA sequence. By generating the complementary sequence, we can obtain the original viral RNA sequence, allowing us to study and analyze the genetic information of the virus effectively.


## Features

- Generate the complement sequence of a given nucleic acid sequence.
- Create the reverse-complement sequence of a given nucleic acid sequence.
- Read a file containing a long DNA sequence.
- Work with complete genomes of the novel coronavirus.

## Installation

1. Make sure you have Python 3 installed on your system. If not, you can download it from the official Python website: [Python Downloads](https://www.python.org/downloads/)

2. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/nucleic-acid-sequence-manipulator.git
Nucleic Acid Sequence Manipulator
```
This Python program allows you to manipulate nucleic acid sequences, specifically DNA and RNA. It provides functionality to construct reverse, complement, and reverse-complement sequences. Additionally, it can read a file containing a long DNA sequence, enabling you to work with complete genomes of the novel coronavirus.

## Usage

To use the program, follow these steps:

1. Ensure you have a the genome file in the FASTA format. You can obtain a complete genome of the novel coronavirus from reliable sources such as GenBank or NCBI. [NCBI Genome Download](https://www.ncbi.nlm.nih.gov/sars-cov-2/)
2. Place the DNA sequence file in the project directory.
3. Open a terminal or command prompt and navigate to the project directory.
4. Run the program with the following command:

```bash
python sequence_manipulator.py
```
The program will prompt you to enter the filename of the DNA sequence file. Provide the filename and press Enter. The program will display:
```bash
NC_045512_China.txt
```
   1. Complementary RNA Sequence
   2. Complete coronavirus cDNA
