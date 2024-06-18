# Identification of single species
3 main strategies:
- DNA-based identification
- Protein-based identification
- Phenotypic identification (selective culturing and microscopy)
## DNA-based identification
- Usually __barcoding__ is required. A barcode is a specific DNA sequence that has been proven useful to distinguish different taxa of a certain group of organisms. 
- For fungi the __ITS (Internal Transcribed Spacer__), sequences between 18S and 28S rRNA ) is used for that. They have stable ends, so that a few different primers can cover all fungi while at the same time there are variable regions which provide specificity. Their size (525-700bp) is convenient in the sense that they can be easily amplified. There is already a big database of fungi with the corresponding ITS sequence. 
- The __disadvantages__ mainly are regarding to taxonomy. The variation in this region doesn't match with phylogenetic relatedness, so no phylogenetic tree can be created. 
--> barcodes are only used for identification purposes. 
- The barcode sequence is amplified using [[PCR]]/[LAMP](https://pubmed.ncbi.nlm.nih.gov/32361529/), [[NGS|sequenced]] and searched in __UNITE__ database. 
![[Pasted image 20210814095332.png]]

The taxonomic groups defined by DNA barcode similarity are not classical species, but are called __Species Hypothesis (SH)__, __Molecular Taxonomic Units (MOTU)__ or __Operational Taxonomic Units (OTU)__. Assignment of such a unit to the taxa depends on the chosen threshold of sequence similarity. 

### Database search
  - UNITE is a curated database. Usually the species hypothesis are defined at a threshold of 1.5%
  - NCBI/BLAST database is not curated, it just collects all the findings, which means that the listed organism is not necessarily the sequence "host". Therefore BLAST is not suited for this task. 
## Protein-based identification
[[MALDI biotyping]]
### Advantages
- Fast and cheap (provided that a MS is available)
- Identification of species in most cases possible

### Disadvantages
- In most cases reference spectra have to be generated (based on what you want to identify)
- In most cases the protein pattern changes depending on culture methods
- Not suitable for analysing mixtures --> Isolates are necessary! Some organisms can't be cultivated in vitro


