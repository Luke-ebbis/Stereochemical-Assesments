# Stereochemical-Assesments
A repository to perform stereochemical assesments on PDB models generated by X-Ray Diffraction

**The Scripts**

The ```extract_angles.py``` file extracts the phi and psi angles (Ramachandran angles) from a Protein Data Bank (PDB) file as well as the amino acid residue associated with the torsion angles. This data is then stored in a tsv file. The ```plot.py``` file accesses this tsv file containing the torsion angles and plots these on a Ramachandran plot. This plot can then be interpreted by visually analysing the alpha helix and beta sheet clusters to determine the quality of the protein model.

This repository can help to quickly verify the accuracy of an X-Ray Diffraction protein model so that it can be used for whatever.
