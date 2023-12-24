# Serbian Elections Data Processing Pipeline

## Overview

This repository contains a Jupyter notebook (`elections_data_merging_pipeline.ipynb`) for processing the 2023 Serbian election data. The pipeline automates the renaming, selection, and merging of data from CSV files.

## Setup and Usage

### Required Folder Structure

Ensure your working directory has the following contents:

- An extracted folder named `rezultati_izbora_2023_csv` containing raw CSV files (e.g., `file1.csv`, `file2.csv`, etc.).
- The Jupyter notebook file, `elections_data_merging_pipeline.ipynb`.

Your working directory should have this layout:

- YourWorkingDirectory:
   - rezultati_izbora_2023_csv
   - elections_data_merging_pipeline.ipynb


### Running the Pipeline

1. **Prepare Your Data:**
   - Place the folder `rezultati_izbora_2023_csv` with your CSV files in the same directory as the notebook.

2. **Execute the Notebook:**
   - Open the `elections_data_merging_pipeline.ipynb` notebook.
   - Run all the cells in sequence to process the data.

### Pipeline Process

1. **Rename Files:** Automatically renames the CSV files in `rezultati_izbora_2023_csv` based on extracted patterns.

2. **Data Selection:** Extracts specific columns from each CSV file and saves them in a new folder, `subsections`.

3. **Merge Data:** Merges the selected data into a single DataFrame, saved in a new folder, `merged_csv`.

## Output

The pipeline outputs a merged CSV file with the consolidated data in the `merged_csv` folder.
