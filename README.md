## Python phantom data analysis
This repository consists of a python script to analyze the PET phantom data.

The Society of Nuclear Medicine and Molecular Imaging (SNMMI) provides a cloud-based automated Phantom Analysis Toolkit (PAT). Using that program, one can analyze the PET phantoms data such as the uniform phantom, the NEMA Image Quality phantom, and the ACR phantom data. We can upload the phantom DICOM data for analysis in this program, enter the phantom filling information, and subsequently initiate the analysis. After all these steps, we can download the results.

If one is interested in analyzing the detailed results obtained from NEMA or CTN phantoms, one could work on the analysis.json file. This file is written in JavaScript Object Notation (JSON). The script available in this repository was written to analyze that output file.

The script uses JSON and pandas libraries for data framing and Matplotlib for data visualization.

https://ashok-tiwari.github.io/post/json_parsing/
