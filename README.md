# Bioinformatics Project

**Status: Completed**

A collection of introductory bioinformatics exercises and analyses developed using Python and established bioinformatics tools.

This repository documents practical work in DNA sequence manipulation, next-generation sequencing quality control, and scientific literature analysis.

## 1. DNA Sequence Toolkit

Python implementations of fundamental DNA sequence operations.

- `validate_dna(sequence)` — validates DNA sequences.
- `transcribe_dna(sequence)` — converts DNA into RNA by replacing T with U.
- `reverse_complement(sequence)` — generates the reverse complement of a DNA sequence.

**Run:**

```bash
python3 scripts/dna.py
```

## 2. NGS Quality Control

Quality assessment of paired-end sequencing data from an *E. coli* dataset (`ERR042228`).

**Tools used:**
- FastQC — individual sequencing quality assessment.
- MultiQC — aggregation and visualization of quality-control reports.

**Analysis included:**
- Per-read sequencing quality.
- Phred Q30 statistics.
- Adapter content.
- GC content.
- Comparison of forward and reverse reads.

**Key observation:** Forward reads showed 95.73% Q30, while reverse reads showed 67.40% Q30, indicating a substantial difference in sequencing quality.

Detailed findings: [`notes/ngs_qc_notes.md`](notes/ngs_qc_notes.md)

## 3. Scientific Literature Analysis

Two scientific papers were reviewed to explore DNA structural diversity and molecular conformational variability.

Topics covered:
- Alternative DNA structures.
- B-DNA structural polymorphism.
- Ultra-high-resolution X-ray crystallography.
- Conformational ensembles.
- Relevance of molecular structure to structural bioinformatics.

Detailed records: [`paper_log.md`](paper_log.md)

## Repository Structure

```text
bioinformatics_project/
├── README.md
├── scripts/
│   └── dna.py
├── notes/
│   └── ngs_qc_notes.md
└── paper_log.md
```

## Technologies and Tools

- Python
- Linux (Ubuntu/WSL)
- Git and GitHub
- FastQC
- MultiQC

## Project Conclusion

This project served as an introduction to practical bioinformatics, combining Python-based sequence manipulation, sequencing quality assessment, and scientific literature analysis.

**Project completed: November 2026.**
