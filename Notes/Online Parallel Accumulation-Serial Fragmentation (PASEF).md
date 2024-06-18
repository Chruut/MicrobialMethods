### Online Parallel Accumulation-Serial Fragmentation (PASEF)
PASEF increases the sequencing speed of DDA proteomics severalfold without loss of sensitivity. 

The advantage of using TOF mass analyzers is their high acquisition rate which allows them to be coupled with very fast separation techniques like [Ion Mobility Spectrometry (IMS)](https://en.wikipedia.org/wiki/Ion-mobility_spectrometry), like [[High-Field Asymmetric Waveform Ion Mobility Mass Spectrometry (FAIMS)|FAIMS]]. IMS provides an additional dimension of separation and can increase analysis speed and selectivity. However, many implementations of IMS, such as drift tubes, are challenging because of the device sizes and high voltages involved and they may also limit the proportion of the continuous incoming beam that can be utilized. 

__Trapped ion mobility spectrometry (TIMS)__ reverses the concept of traditional drift tube ion mobility by bringing ions to a rest at different positions in an ion tunnel device, balanced in an electrical field against a constant gas stream. The ions can then be released together downstream into the mass analyzer.  

PASEF synchronizes MS/MS precursor selection with TIMS separation. As precursor ions are trapped and released as condensed ion packages fragmentation of more than one precursor per TIMS scan is allowed, which enables the TOF instruments to operate at the full scan speed with undiminished sensitivity. Additionally to the drastical decrease in measurement time, the required sample amount also diminishes, allowing the instrument to be used in proteomic studies with very little starting amount. 

PASEF is expected to not only benefit label-free quantification, but also for instance isobaric labeling with TMT, iTRAQ or EASI-tag. These approaches should additionally benefit from the ion mobility separation itself as it increases the purity of the isolation window and thereby reduces potential artifacts from co-eluting and co-isolated precursor ions. 

TIMS-PASEF provides an efficient way to generate comprehensive libraries of peptide collisional cross sections (CCS) which may eventually enable the __in silico prediction of CCS values__ by deep learning algorithms. Furthermore, the very high precision of the CCS measurements with TIMS opens new avenues for spectral library-based identifications, in which the CCS parameter adds important evidence either on the MS level or, in data-independent acquisition strategies, also on the MS/MS level.
![[Pasted image 20210811101328.png]]

## Advantages
- Highly selective MS/MS traces
- High sensitivity because of noise reduction
- Close to 100 % duty cycle operations
- High assignment rate and completeness (reduced undersampling problem)
- Requires very little sample starting amounts
- Measures CCS