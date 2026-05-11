# AntiBP: Prediction of Antibacterial Peptides

Welcome to the official repository for AntiBP, a computational platform developed for the analysis and prediction of antibacterial peptides using machine learning techniques such as Support Vector Machines (SVM), Artificial Neural Networks (ANN), and Quantitative Matrices (QM).

Web Server:  https://webs.iiitd.edu.in/raghava/antibp/

ZENODO : https://doi.org/10.5281/zenodo.20080300

---

## Brief Description

Antibacterial peptides are important components of the innate immune system and serve as natural defense molecules against pathogenic bacteria. Due to the rapid emergence of antibiotic-resistant bacterial strains, antibacterial peptides have become promising candidates for the development of next-generation peptide therapeutics.

AntiBP was developed to computationally predict antibacterial peptides directly from amino acid sequences. The study analyzed experimentally validated antibacterial peptides to identify residue preferences, positional patterns, and compositional biases associated with antibacterial activity.

The prediction models were developed using machine learning approaches including Support Vector Machine (SVM), Artificial Neural Networks (ANN), and Quantitative Matrices (QM). The system utilizes N-terminal residues, C-terminal residues, and combined terminal sequence information to classify peptides as antibacterial or non-antibacterial.

The platform provides tools for peptide prediction, antibacterial region mapping, and peptide screening, making it useful for peptide therapeutics, computational biology, and antimicrobial drug discovery research.

---

## Citation

Lata, S., Sharma, B. K., & Raghava, G. P. S. (2007).  
Analysis and prediction of antibacterial peptides.  
BMC Bioinformatics, 8, 263.  
https://doi.org/10.1186/1471-2105-8-263

---

## About the Platform

AntiBP is a sequence-based prediction server designed to identify antibacterial peptides using computational learning techniques.

The platform focuses on:

* Prediction of antibacterial peptides
* Analysis of terminal residue patterns
* Mapping antibacterial regions in proteins
* Computational peptide screening

The study analyzed:

* 486 antibacterial peptides from APD database
* 436 non-redundant antibacterial peptides
* Random non-antibacterial peptide datasets

---

## Key Features

Machine Learning Models

* Support Vector Machine (SVM)
* Artificial Neural Networks (ANN)
* Quantitative Matrix (QM)

Prediction Strategies

* N-terminal residue analysis
* C-terminal residue analysis
* Combined N+C terminal prediction

Sequence Analysis

* Residue positional preference
* Amino acid composition analysis
* Binary pattern encoding
* Consensus prediction models

---

## Dataset Information

Main Dataset

* 436 antibacterial peptides
* 436 random non-antibacterial peptides

Terminal Datasets

* NT5, NT10, NT15
* CT5, CT10, CT15
* NTCT15 combined dataset

Independent Dataset

* 39 experimentally validated antibacterial peptides from Swiss-Prot

---

## Important Residue Preferences

Preferred residues in antibacterial peptides:

* Glycine (G)
* Lysine (K)
* Arginine (R)
* Leucine (L)
* Isoleucine (I)
* Cysteine (C)

Under-represented residues:

* Aspartic acid (D)
* Glutamic acid (E)
* Serine (S)
* Proline (P)

Observations:

* Positively charged residues are highly preferred
* N and C termini both contribute to antibacterial activity
* C-terminus plays a major role in membrane interaction

---

## Performance Summary

SVM Models

| Model | Accuracy |
|---|---|
| N-terminal (15 residues) | 87.85% |
| C-terminal (15 residues) | 85.16% |
| N+C terminal | 92.11% |

QM Models

| Model | Accuracy |
|---|---|
| N-terminal | 84.78% |
| C-terminal | 82.03% |
| N+C terminal | 90.37% |

ANN Models

| Model | Accuracy |
|---|---|
| N-terminal | 83.63% |
| C-terminal | 77.34% |
| N+C terminal | 88.17% |

Consensus Model

* Best Accuracy = 92.58%

---

## Methodology

Prediction models were developed using:

* Five-fold cross validation
* Independent dataset testing
* Binary pattern encoding
* Amino acid composition analysis

Software & Tools

* SVMlight
* Stuttgart Neural Network Simulator (SNNS)
* Quantitative Matrix methods

---

## Applications

* Antibacterial peptide discovery
* Antibiotic resistance research
* Peptide therapeutic design
* Computational biology research
* Antimicrobial drug development

---

## Contact & Authors

Prof. G. P. S. Raghava
Email: raghava@iiitd.ac.in
Indraprastha Institute of Information Technology Delhi

raghava@imtech.res.in
Institute of Microbial Technology (IMTECH)  
Chandigarh, India

---

## License

This work is distributed under the  
Creative Commons Attribution License.

---

## Acknowledgements

Supported by:

* Council of Scientific and Industrial Research (CSIR)
* Department of Biotechnology (DBT), Government of India

Special thanks to researchers contributing to antibacterial peptide databases and antimicrobial peptide research.

---

## Source

Paper extracted from uploaded PDF. :contentReference[oaicite:0]{index=0}
