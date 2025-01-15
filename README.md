# CryptAnalysis

## Project Overview

An exploration of cryptographic concepts, including modular exponentiation, RSA algorithm analysis, and brute-force password cracking techniques. This repository contains Python implementations, performance evaluations, and visualizations as part of the **MATH 359 project for the 2024/25 academic year.**

- Modular exponentiation algorithms.
- Performance evaluation of the RSA algorithm and its complexity.
- Brute-force password cracking techniques for different scenarios.

Our goal is to implement these concepts using Python, analyze their performance, and present the findings in a well-documented and collaborative manner.

---

## Table of Contents

1. [Getting Started](#getting-started)
2. [Features](#features)
3. [Usage](#usage)
4. [Project Structure](#project-structure)
5. [Contributors](#contributors)

---

## Getting Started

### Prerequisites

To run the code in this repository, ensure you have the following installed:

- Python 3.8 or higher
- Jupyter Notebook
- Required libraries (listed in `requirements.txt`)

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Programming-Sai/CryptAnalysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd CryptAnalysis
   ```
3. Create a Vitual Environment

   ```bash
   python -m venv .crypt-venv
   ```

4. Activate the Venv

   ```bash
   .\.crypt-venv\Scripts\activate # Windows

   # OR

   source .crypt-venv/bin/activate # MacOS/Linux
   ```

5. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Features

- **Modular Exponentiation Algorithm**: Python function implementation with performance comparison.
- **RSA Decryption Complexity**: Analyzing brute-force decryption time for varying key sizes.
- **Password Cracking**: Brute-force attack simulations for numeric and alphanumeric PINs.
- **Visualization**: Graphs for performance comparisons and password cracking times.

---

## Usage

1. Open the Jupyter Notebook in the project folder:
   ```bash
   jupyter notebook CryptAnalysis.ipynb
   ```
2. Run the cells to view the implementation, results, and visualizations.
3. Edit or contribute by creating new branches for your work.

---

## Project Structure

```
CryptAnalysis/
│
├── data/                   # Folder for any sample data used (if applicable)
│
├── notebooks/              # Folder for Jupyter notebooks
│   ├── task_1_modular_exponentiation.ipynb   # Notebook for task 1
│   ├── task_2_rsa_analysis.ipynb             # Notebook for task 2
│   ├── task_3_password_cracking.ipynb        # Notebook for task 3
│
├── scripts/                # Folder for Python scripts
│   ├── modular_exponentiation.py  # Python code for task 1 (modular exponentiation)
│   ├── rsa_analysis.py          # Python code for task 2 (RSA decryption)
│   ├── password_cracking.py     # Python code for task 3 (brute-force cracking)
│
├── results/                # Folder for storing any output data, plots, or reports
│   ├── rsa_analysis_results.csv  # CSV files for RSA analysis results
│   ├── password_cracking_times.csv  # CSV file for password cracking times
│   └── performance_plots/      # Folder for storing graphs and charts
│
├── README.md               # Project overview, installation instructions, and usage
├── .gitignore
└── requirements.txt        # List of dependencies needed for the project (if applicable)

```

---

## Contributors

This project is a group effort by the following team members:

_Add your name and ID here_

- **[Menah Lartey Isaiah Nii Lartey] - [11222100]**: Modular Exponentiation
  <br>
  <br>

> [!NOTE] > _If you're a team member, ensure you’ve been added as a collaborator. Reach out if you need access._

---
