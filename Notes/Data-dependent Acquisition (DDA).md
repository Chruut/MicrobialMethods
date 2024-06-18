# Data-dependent Acquisition (DDA)
The goal of DDA is to identify as many peptides as possible, one at a time. The highest peaks in the MS1 spectrum are selected for isolation, with an isolation window of ~1 Th 
(Dalton/elementary charge). Peptides in this window are selected based on their spectrum intensity, isolated and [[Data Aquisition#How fragmentation works|fragmented] for readout in the MS2 spectra. 

For __quantification__, the peptides in the MS1 spectrum are continuously monitored via their peak intensities in the spectra. the area under the curve is typically used for peptide quantification.

## Disadvantages
 (Jian Guo 2020)
- __Missing values__ arise from the stochastic sampling
- Metabolic features of interest with low MS abundance may never be selected for fragmentation and will have no MS2 data associated with them.
-  Since the MS instrument allocates a large portion of its acquisition time for MS2 spectra generation, the signal intensity for MS1 features is reduced. This causes a fundamental problem for the detection and quantification of low abundance metabolites in DDA mode.


[Brenes, 2019](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6773557/pdf/zjw1967.pdf):
_High-throughput, shotgun proteomics, using data dependent acquisition (DDA), now enables the comprehensive study of proteomes, allowing the identification of 10,000 or more proteins from cells and tissues. However, to achieve such deep proteome coverage using DDA, extensive prefractionation of extracts before mass spectrometry (MS) analysis is frequently required. To evaluate statistically the significance of the resulting data, a minimum of 3 replicates for each sample/condition is also necessary._