# Data ELT Process

## Overview

This project implements a data ELT (Extract, Load, Transform) process using Python and pandas. The primary goal is to clean, transform, and analyze employee training performance data from a relational database and prepare it for analysis.

## Requirements

- Python 3.6 or higher
- Pandas
- Jupyter Notebook
- Logging

## Getting Started

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Install the required packages:
   ```bash
   pip install psycopg2 pandas openpyxl python-dotenv logging
   ```
3. Create .env file by copying the .env.example file and enter your db details

### Usage

1. Open the Jupyter Notebook.

2. Load the necessary data files into DataFrames within the notebook.

3. The results are logged in `elt_process.log`, which records all significant steps and any errors encountered.

## Logging

All actions and errors are logged in the `elt_process.log` file. This log includes:

- Start and end times of each function
- Number of records processed
- Any errors encountered during processing
