# *Evaluating Calibration-Based Digital Twins for IBM Quantum Hardware Simulation*: Additional Files

This project contains files and additional important information for the research described in paper "*Evaluating Calibration-Based Digital Twins for IBM Quantum Hardware Simulation*", authored by Edgars Bautra, Maksims Dimitrijevs, and Abuzer Yakary.

## 1. Included content

There are 3 PDF files containing data in the form of tables:
- File `Similaroty matrices.pdf` contains matrices for all 24 experiments;
- File `Table for Shot Budget Selection.pdf` contains full table of experiment result data for shot count selection;
- File `Table for Simulation Method Comparison.pdf` contains similarity matrix for comparing all 3 valid simulation methods.

Folder `results/counts` contains the results of experimental runs on QPUs and simualtors with noise models:
- Folder `json` contains sorted results as separate JSON files;
- File `all_counts.py` contains all results in the form of a single variable, gathered from separate files located in the folder `json`.

Folder `assets` contains:
- All 3 randomly generated five-qubit circuits as .qpy files, located inside of subfolder `circuits`;
- CSV calibration data, that was used when conducting experiments, located inside of subfolder `csv_files`.

Finally, the file `code_examples.ipynb` contains important code fragments that were used during the research (also including quantum circuits for the experiments).

## 2. Software versions

During the practical part of this research, the following software versions were used:
- Python: **3.13.2**
- qiskit: **2.0.0**
- qiskit_aer: **0.17.0**
- ibm_qiskit_runtime: **0.38.0**
