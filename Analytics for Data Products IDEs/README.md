# Toolwindow Usage Analysis

This project analyzes IDE tool window usage data to determine if there's a significant difference in session duration based on how the tool window was opened (manually vs. automatically).

## Project Structure

```
.
├── toolwindow_data.csv          # Original raw data
├── cleaned_sessions.csv         # Processed session data (generated)
├── project.ipynb                # Main analysis python notebook (Jupyter)
├── ANALYSIS_SUMMARY.md          # Detailed analysis report
└── README.md                    # This file
```

## Setup Instructions

### Prerequisites

You need Python 3.7 or higher with the following packages:

- pandas
- numpy
- scipy
- matplotlib
- seaborn

### Installation

#### Option 1: Using pip

```bash
pip install pandas numpy scipy matplotlib seaborn
```

#### Option 2: Using conda

```bash
conda install pandas numpy scipy matplotlib seaborn
```

#### Option 3: Using requirements file

Create a `requirements.txt` file with:
```
pandas>=1.3.0
numpy>=1.21.0
scipy>=1.7.0
matplotlib>=3.4.0
seaborn>=0.11.0
jupyter>=1.0.0
```

Then install:
```bash
pip install -r requirements.txt
```

