# Machine Learning Discovery of PBFO as Organic Cathode Material

## Project Description
This repository hosts the code and data for the paper "AI-Driven Design of a Flexible Highly Conductive Additive-Free Polymer Cathode Material." It details a machine learning approach that identified isoindigo and isoxindigo derivatives, leading to the design of poly-benzodifurandione (PBFO) as a high-performance, organic cathode material for lithium-ion batteries.

## Project Structure
00_PBFO-ML-paper/
│
├── README.md # This file
├── data/ # Data directory
│ ├── raw/ # Raw, immutable data
│ │ ├── OrganicElectrodesPublications.csv
│ │ ├── OrganicElectrodesAll.csv
│ │ └── dataMerge # A folder with a notebook to prepare OrganicElectrodesAll.csv
│ ├── augmented_data # A folder with a notebook to prepare augmented data
│ └── ZINC_database-representative_Mol # ZINC database and representative molecules for similarity screening
├── notebooks/ # Jupyter notebooks for exploration
│ ├── EDA_971_molecules_experimental_data
│ ├── Screening_similarity
│ ├── Data_Agmt_and_3_models
│ └── Best_Model4_MolFeatures
└── requirements.txt # Python dependencies

### Prerequisites
- Python 3.9.19

## Citation
If you use this code or data in your research, please cite our paper.
