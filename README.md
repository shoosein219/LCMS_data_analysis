# LCMS_data_analysis_examples

## this page is a work-in-progress: last updated - Oct 2023

### 1. Metaproteomics Analysis from data output from liquid chromotography mass spectrometry run quantifying proteins involved with ZVS production in sulfate-reducing microorganisms using the ZVS pathway vs sulfate reduction pathway.

[data](https://www.ebi.ac.uk/pride/archive/projects/PXD040825)
Data aquired from PRoteomics IDEntifications Database from publication submission DOI: 10.1073/PNAS.2220725120

Understanding how dissimilatory sulfate reduction from diverse sulfate-reducing microorganisms can be generated with zero-valent sulfur(ZVS), as opposed to sulfate reduction to sulfide. Utilization of the ZVS pathways in processing sulfate can be induced at greater levels by increasing salinity of media for growing sulfate-reducing microorganisms. Furthermore, ZVS products produced by sulfate-reducing microorganisms can support the growth of other ZVS-metabolizing microorganisms, yielding its importance to the sulfur biogeochemical cycle. 

### Pipeline used for proteomics data analysis
(1) Raw data pre-processing: https://github.com/MannLabs/alphapept
also: TidyMS in Python
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7602939/

(2) Peak picking and assignment: https://openms.de/

(3) Database search: UniProt

(4) Quantification: sprectral counting and peptide intensity

(5) Data Analysis: limma

(6) Visualization: MSnbase


### 2. Non-targeted metabolic data analysis from synthetic bacteria communities on plant leaves

non-targeted metabolic data analysis using data from synthetic bacteria communities on plant leaves

[data](https://massive.ucsd.edu/ProteoSAFe/dataset.jsp?task=603ea096517b4d5897ead98b070fc7f0)

Using the NP3 MS workflow:
https://github.com/danielatrivella/NP3_MS_Workflow


