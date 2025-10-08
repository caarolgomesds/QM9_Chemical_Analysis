# Hands-on: molecular data reading

This report details the steps of the QM9 dataset analysis script, providing additional context and insights based on scientific literature.

Create functions for:
1. Load and unpack the QM9 dataset
2. Open XYZ files and extract the properties and SMILES (and other
features you find relevant for the tasks below)
1. SMILES must be validated using the RDKit, invalid SMILES must be ignored
2. Generate the canonical SMILES (which must be saved)
3. Create a dataframe (pandas) to store the QM9 samples (SMILES and
properties)
4. Plotting histograms for all properties
5. Plotting histograms for the molecular composition and size
6. Correlation analysis considering: all properties, number of atoms, and
molecular weight
