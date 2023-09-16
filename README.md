# LCMS_data_analysis
Analysis from data output from liquid chromotography mass spectrometry run

[data](https://www.ebi.ac.uk/pride/archive/projects/PXD040825)
Data aquired from PRoteomics IDEntifications Database from publication submission DOI: 10.1073/PNAS.2220725120

Understanding how dissimilatory sulfate reduction from diverse sulfate-reducing microorganisms can be generated with zero-valent sulfur(ZVS), as opposed to sulfate reduction to sulfide. Utilization of the ZVS pathways in processing sulfate can be induced at greater levels by increasing salinity of media for growing sulfate-reducing microorganisms. Furthermore, ZVS products produced by sulfate-reducing microorganisms can support the growth of other ZVS-metabolizing microorganisms, yielding its importance to the sulfur biogeochemical cycle. 

# Pipeline used for data analysis
(1) Raw data pre-processing: https://github.com/MannLabs/alphapept
(2) Peak picking and assignment: https://openms.de/
(3) Database search: UniProt
(4) Quantification: sprectral counting and peptide intensity
(5) Data Analysis: limma
(6) Visualization: MSnbase
