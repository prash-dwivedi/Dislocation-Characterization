# Dislocation Characterization in OVITO

This OVITO Python script analyzes dislocation segments extracted from a crystal structure (e.g., using the DXA algorithm) and classifies them into screw, edge, or mixed types based on the angle between their line direction and Burgers vector. It then calculates the total length of each dislocation type and stores the results as attributes in the OVITO data pipeline.

## Features

- **Dislocation Classification:** Accurately classifies dislocation segments into screw, edge, or mixed types.
- **Length Calculation:** Computes the total length of each dislocation type.
- **Attribute Storage:** Stores the calculated lengths as attributes in the OVITO data object for further analysis or visualization.
- **Customization:** Easily adjustable angle thresholds for dislocation classification.

## Requirements

- OVITO with Python scripting enabled.
- NumPy library.

## Usage

1. **Load your crystal structure data** into OVITO (e.g., a CNA file with dislocations extracted using the DXA algorithm).
2. **Copy the script code** into a new OVITO Python modifier.
3. **Apply the modifier** to your loaded data.
4. **Run the simulation** or analyze the data. The calculated dislocation lengths will be available as attributes in the data pipeline.

#If you use this script in your research, please cite the following articles:

[DOI: 10.1016/j.jnucmat.2024.155289](https://doi.org/10.1016/j.jnucmat.2024.155289)
[DOI: 10.1016/j.jnucmat.2024.155042](https://doi.org/10.1016/j.jnucmat.2024.155042)
