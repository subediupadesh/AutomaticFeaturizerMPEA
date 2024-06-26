# For Web APP:
Visit the website : https://imcathea.streamlit.app

# AutomaticFeaturizerMPEA
AutomaticFeaturizerMPEA.pynb is an interactive computational environment developed in python programming language to compute the properties of Multi Principal-component Element Alloy (MPEA) system.

The code present in the .ipynb file is capable of firstly extracting composition feature from the name of MPEA and then compute thermodynamic/physical and chemical properties using these composition features. The properties that can be automatically calculated and featurized by the code are: 
1. Valence Electron Concentration
2. Average Melting Temperature
3. Enthalpy of Mixing
4. Entropy of Mixing
5. Electronegativity
6. Atomic size difference
7. Omega parameter  
8. 41 elemental composition

The primary source used for the calculation of these alloy properties are taken from two python libraries: "pymatgen" and "matminer". 

The AutomaticFeaturizerMPEA.pynb is not only capable of calculating an alloy's properties but also featurizes them along with the composition and export it as a .csv file for further machine learning training process. The AutomaticFeaturizerMPEA.pynb file consists of two parts:

1. "Part 1": A sample set of 25 MPEAs is used to demonstarte how to calculate & featurize the porperties and composition of alloy, save the calculated values in a .csv file.
2. "Part 2": The alloy property of a single MPEA "Ti0.8CoCrFeNiCu" is calculated using the same code, if one needs to calculate them for a single MPEA at a time (as in our GUI application IMCATHEA https://github.com/subediupadesh/IMCATHEA) 



The repository also consists two "CSV" files:

1. "MPEA_data.csv" file is the sample set of 25 collected MEPA observations with their source and phase information in one hot encoding method for which we want to calculate their properties and featurize them.
2. "Featurized_MPEA.csv" file is the processed ready to train file which consists of MPEA, their properties and composition featurized in special order. It is the final file generated by the AutomaticFeaturizerMPEA.pynb python file.


## How to cite Automatic Featurizer libraries:
If you use the automatic featurizer libraries in your research, please cite:

Subedi, U.; Coutinho, Y.A.; Malla, P.B.; Gyanwali, K.; Kunwar, A. Automatic Featurization Aided Data-Driven Method for Estimating the Presence of Intermetallic Phase in Multi-Principal Element Alloys. Metals 2022, 12, 964. https://doi.org/10.3390/met12060964

## For the Full Open Access Paper:
https://www.mdpi.com/2075-4701/12/6/964/htm
