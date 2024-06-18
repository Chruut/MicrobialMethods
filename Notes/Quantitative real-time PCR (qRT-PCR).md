## Quantitative real-time PCR (qPCR, qRT-PCR)
![[Pasted image 20210812111639.png]]
### Some Definitions
- __Real-time PCR__ (also called "Quantitative PCR", __qPCR__) measures (DNA!) PCR products over the course of the reaction (in contrary to end-point-PCR). 
- It is not the same as __RT-PCR__ (Reverse Transcription-based PCR). 
- Further, __qRT-PCR__ is Reverse Transcription followed by qPCR. This is used to measure transcription levels!
- __Threshold__ is a level which signals a statistically significant difference to background level. 
- __Cycle threshold (Ct)__ is the number of cycles necessary to reach the threshold level. The bigger the Ct, the lower the amount of template was available.


qPCR (real-time PCR) and qRT-PCR rely on the exponential rate of PCR amplification. The amount of amplified product over the number of PCR cycles shows a sigmoidal relationship, because dNTPs and primers are exhausted over time which leads to saturation of the product. The greater the amount of template, the quicker the saturation point is reached and thus the number of PCR cycles implies on the amount of template material. The measure is statistically quantified by using the cycle threshold.
![[Pasted image 20210812111330.png]]

qRT-PCR can be used to determine transcription levels in a sample. It can also be used for other purposes, f.i. ==to quantify a specific genome from a sample (!very important!)== or to quantify tagged strains (DNA Tags).

## Usage of fluorophores
Real-time PCR uses fluorophores to detect levels of the amplified DNA:
- __SYBR-Green__ which unspecifically binds to dsDNA and increases fluorescence of the sample. Primer dimers interfere with the signal. 
- __TaqMan__ probes are hydrolysis probes that are designed to increase specificity of qPCR, in contrast to SYBR-Green. The probe consists of a "Reporter" fluorophore at the 5' end and a "Quencher" at the 3' end. The TaqMan probe anneals within the amplified DNA region and is degraded during the process of elongation. This sets the Reporter free, allowing the fluorophore to be detected. 
![[Pasted image 20210812112827.png]]
- [FRET probes](https://en.wikipedia.org/wiki/Förster_resonance_energy_transfer)

## (Dis-)advantage
Real-time PCR has relatively low througput, as only a handful of genes can be analyzed at a time. Microarrays can potentially profile the transripts of an entire genome, __but the sequences must be known__ and they have to be spotted onto the GeneChip. 
