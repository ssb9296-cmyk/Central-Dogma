Central Dogma Automation Tool
Automating DNA to Protein Translation for Genomic Research
📌 Project Overview
This project provides a Python-based implementation of the Central Dogma of Molecular Biology. It automates the transcription of DNA sequences into RNA and the subsequent translation into functional protein sequences using a customizable codon map.

Key Features:

DNA Validation: Handles raw genomic strings.

Transcription: Accurate T → U conversion.

Translation: Efficient triplet-codon mapping for protein synthesis.

AI-Enhanced Development: Developed using an AI-assisted workflow to optimize code efficiency and documentation.

🧪 Scientific Context
In pharmaceutical research and diagnostic labs, manual translation of genetic variants is prone to human error. This tool serves as a foundational script for automating the processing of small-scale sequencing data, ensuring reproducibility and data integrity.

🛠️ Technical Stack
Language: Python 3.x

Environment: Google Colab / Jupyter Notebooks

Libraries: (Optional: Biopython for future scaling)

AI Tools: GitHub Copilot for code structure and logic optimization.

🚀 How to Run
Open the notebook in Google Colab.

Input your target DNA sequence in the dna_sequence variable.

Run the cells to view the transcribed RNA and translated Protein output.

Python

# Example Usage:
dna_sequence = "ATGGCCATTGTAATGGGCCGCTGAAAGGGTGCCCGATAG"
# Output: Translated Protein: MAIVMGR*KGAR*
📈 Future Roadmap
[ ] Add support for reading multi-line FASTA files.

[ ] Integrate GC-Content calculation for sequence quality control.

[ ] Implement an AI-powered summary of protein function using clinical databases.
