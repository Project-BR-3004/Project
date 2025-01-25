Data Curation and Preprocessing Overview
In this project, there are four distinct files:

Chaos File: This file is considered negligible for the current task and is excluded from further processing at the moment.

File 1 and File 2 (Curated Files):

These files are individually curated, which involves several key preprocessing steps:
Anonymization: Sensitive data is anonymized to ensure privacy and compliance.
Handling Missing Values: Any rows with missing data are removed to ensure clean and complete datasets.
Fixing Minor Errors: Small spelling mistakes and formatting errors are corrected.
After these steps, the two curated files are combined into a single dataset and undergo another round of curation to ensure data consistency and quality.
Label Encoding:

Once the data is curated, we perform label encoding (as detailed in the encoded_coding_file.py). This process converts categorical labels into numerical values, which makes the data easier to process for machine learning algorithms.
Final Combined Dataset:

The final file, named variants&metadata_fixed1.csv, contains the label-encoded and combined dataset. This file is the cleaned and processed version that was used as input for the various machine learning algorithms.
