# BP219-Finalproject
# Introduction
Structural techniques have improved over time and we are curious as to how the resolutions of structures solved has changed throughout the decades. This code was designed to be able to read multiple pdb files and extract the deposition date, resolution, and structure method from each of those files. From this data, it is able to output histograms containing the resolution (x) and # of structures (y) over different date ranges.
# Packages Needed
- Bio
- Bio.PDB.parse_pdb_header
- os
- pandas
- numpy
- matplotlib.pyplot
# How to Use
1. Download pdb files of interest and place into one folder
2. Input path to pdbfiles onto dirpath variable and other places the path is called
3. Execute code
4. This will output histograms of structures within these date ranges:
 - 1976-89;1990-2009;2010-2014;2015-2022 (X-ray Crystallography)
 - 1990-2009; 2010-2014; 2015-2022 (electron microscopy)
 - this will also save each histogram as a png file

FINAL WORKING NOTEBOOK IS: "final.ipynb"
