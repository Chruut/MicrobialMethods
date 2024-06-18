# What is proteomics?

The study of proteins:
1. When and where they're expressed
2. How they're modified
3. How they're involved in metabolic pathways
4. How they interact with one another ([[Protein function analysis]])
- Marc Wilkins (1994)

--> "A comprehensive quantitative description of protein expression and its changes under the influence of biological perturberances" - N. Leigh Anderson

Creating proteomics samples comes with a certain complexity which is mainly due to the dynamic range of different protein abundances. With that comes a certain sensitivity problem. But this issue can be coped via the [[undersampling problem]].

Although transcriptomic analyses are already rich in information, they generally fail to capture any post-transcriptional processes. It is therefore very important to complement these transtript-based insights with quantitative protein information in order to understand biological functioning.
_- Schmidt et al 2015_

__Bottom-up proteomics__: proteins are first digested into peptides and the peptides analyzed with the mass spectrometer

__Top-down proteomics__: the analysis of intact proteins via mass spectrometry

There are five dimensions which need to be considered when comparing proteomic methods:
- Metabolite Coverage
- Quantitative Precision
- Resolution
- Percentage of MS2 coverage (identification) out of total number of precursors
- Convenience


Mass spectrometry, in combination with protein and peptide separation methods, allows the efficient __qualitative__ identification of proteins in complex mixtures. But direct, non-relative __quantitative__ data of proteins, allowing a comparison of different proteins within and between samples, are still difficult to obtain on a large scale. Various Shotgun approaches seem to be most fruitful at the moment as suitable tools for large scale proteome analysis. 
![[Pasted image 20210804072405.png]]
The right side is all about Sample Preparation

# Shotgun proteomics
_Ishihama, Y. et al. (2008)_

Shotgun proteomics aims to identify proteins in a sample based on protease digestion of the whole sample, followed by peptide separation and identification by LC-MS/MS with multidimensional sample separation. However, in contrast to the 2D-Gel Electrophoresis approaches where individual spots are being analyzed, information about protein abundances is initially unavailable in the shotgun approaches. 
![[Pasted image 20210810180425.png]]

## General Workflow in Shotgun Proteomics
![[Pasted image 20210809161444.png]] 
1. [[Biological Question]]
2. [[Sample Preparation]]
3. [[Data Aquisition]]
4. [[Data Analysis]]
5. [[Data Validation]]
6. [[DNA Sequencing]]

## Shotgun methods
### Label-free methods
- [[Data-dependent Acquisition (DDA)]]
- [[Data-independent Acquisition (DIA)]]

Label-free methods are less expensive than labeled quantitative proteomics and have no limits regarding the number of samples that can be analyzed and compared. 

Summary Full scan vs. DDA vs. DIA
![[Pasted image 20210813175859.png]]

### Quantification of complex protein mixtures
Peptide quantification in label-free methods rely on spectral counting/signal intensity measurements which is not absolute.  To overcome this limitation several strategies have been used: 
- Comparing spike sizes to reference peptides with known concentrations 
- Comparison of the [[xPAI parameter]]. When using the xPAI method, an alternate [[LCMS(E) scanning]] method is available which describes how to obtain a single point calibration for the mass spectrometer that is applicable to the subsequent absolute quantification of all other characterized proteins within the complex mixture.
- __Protein Abundance Index (PAI)__ is the number of peptides per protein normalized by the experimentally registered  number of peptides. As the PAI correlates better with the logarithm of protein concentration it's preferably being defined as __exponentially modified PAI (emPAI)__. 

#### (Dis-)Advantages
Although such a method of concentration determination may not be expected to be overly precise, the accuracy of emPAI-derived concentration measurements has been shown to lie within an error range of only a factor of maximally 3.4 for 46 proteins in whole cell lysates of murine neuroblastoma cells and is therefore in the same range or better than protein concentration measurements based on staining methods. 

A major advantage is that the emPAI based protein concentration is automatically and quickly available for all proteins identified by MS without the need of any additional experimental setup. A similar approach was reported for the membrane proteome of _S. cerevisiae_, where protein concentrations were estimated by using the number of obtained spectra per protein divided by the length of the protein.

Determination of __emPAI__-based direct protein abundances can also be carried out in combination with some of the more accurate relative abundance measurement methods, e.g. iTRAQ, 18O-labeling or SILAC, since these do not introduce a detection bias towards certain peptides in the protease digested samples. ICAT, on the other hand, is dependent on the presence of a cysteine in a peptide in order for it to be detected, and cannot therefore easily be combined with the emPAI approach. The specificity to only a subset of all peptides renders this relative quantification method less well suited for concurrent direct protein quantification.

## Labeled methods
- [[Stable Isotope Labeling Methods]] (SILAC)
- [[Multiplexed Proteomics]] (Isobaric tags)
- [[High-Field Asymmetric Waveform Ion Mobility Mass Spectrometry (FAIMS)]]
- [[Online Parallel Accumulation-Serial Fragmentation (PASEF)]]


# Protein Interaction Analysis
![[Pasted image 20210811181513.png]] 
- [[NestLink]] (Peptide Barcodes)
- [[Affinity Purification Mass Spectrometry (AP-MS)]]
- [[Proximity Labeling (BioID)]]
- [[MAC-tag]]
- [Protein Complex Immunoprecipitation (Co-IP)](https://www.wikiwand.com/en/Immunoprecipitation)
- [Cross-linking Mass Spectromtery (CL-MS)](https://www.research.ed.ac.uk/en/publications/cross-linking-mass-spectrometry-methods-and-applications-in-struc)
- [Chromatin immunoprecipitation(ChIP)](https://www.wikiwand.com/en/Chromatin_immunoprecipitation) (investigate DNA interaction)


# Analysis of Post-translational Modifications

Common PTMs:
- Phosphorylation
- Glycosylation
- Ubiquitination (Pupylation)
- Sumoylation
- Methylation
- Acetylation



## Problems and solutions 
Which PTM you want to analyze must be defined before the experiment starts!
- They are rather rare --> [[Enrichment strategies]]
- The peptides are less good fragmenting & ionizing --> Different MS/MS fragmentation techniques are required. Certain modifiers can increase ionization efficiency
- Some PTMs are labile and can be lost ([pSTY](https://www.sciencedirect.com/science/article/pii/S1535610818303581), glycosylation) --> Adaptation of the sample prep conditions
- Problems with the dynamic range --> High Mass accuracy and resolution
- Ambiguous: Often there are multiple potential targets for the PTM
- They are very dynamic/time-sensitive
- They interfere with surfaces




# Applications of Proteomics
- [[Mass Cytometry (CyTOF)]]
- [[MALDI-TOF biotyping]]
- [[PCR-ESI-MS]]
- [[Imaging MS (IMS)]]
- [[MS in surgery]]






# Shotgun lipidomics
https://en.wikipedia.org/wiki/Shotgun_lipidomics

![[Pasted image 20210913215749.png]]
![[Pasted image 20210913215807.png]]