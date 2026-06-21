# eDNA Barcoding Pipeline

Simple eDNA sequence analysis for species detection.

## Problem

Environmental DNA analysis allows determining which birds drank water from a lake sample. Labs deliver raw, massive FASTQ files with sequences that field biologists don't know how to analyze and compare against global databases.

## Solution

Simple local Python script designed for biologists that cleans raw sequences and automates batch queries to NCBI BLAST database, returning clear taxonomic reports of species present.

## Technical Stack

- `Biopython` library (`Bio.Blast.NCBIWWW`)
- Sequence quality filtering via Phred scores
- Genetic match percentage mapping

## Status

🚧 Planning

## Community

Join the discussion:

[![Matrix](https://img.shields.io/badge/Matrix-%23edna-barcoding-black?logo=matrix)](https://matrix.to/#/#edna-barcoding:matrix.org)

## License

MIT — see [LICENSE](LICENSE)
