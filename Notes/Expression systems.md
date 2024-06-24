# Applications of (recombinant) protein expression
- Pharma: therapeutics, antibodies, analytics, …
- Agronomy: therapeutics, food additives,
- Research: structural and biophysical studies, protein isolates
- Functional assays
- Biomarkers
- Mechanistic (enzymatic) studies in vitro and in vivo

In research they're used for structural and biophysical studies. The purified (a necessity) proteins can then be used to assess functional or enzymatic activity (functional assays). They can also be used as biomarkers.


# Features of an efficient protein expression system
Efficient expression and purification of recombinant proteins relies on optimized vectors and host properties:
- __Inherent problems__ in recombinant protein expression are [[codon bias]], [[protein toxicity]] or [[insolubility]]. 

- If the expression of the protein needs to be turned on and off, especially if the produced protein is toxic to the host, use a vector that has regulatory elements, such as the __lac repressor__, and ensure that strain expresses the operator that produces the inducers OR the transporters which transport the inducers into the cell. 

- Critical features of expression vectors are well [tunable promoters](https://reader.elsevier.com/reader/sd/pii/S0958166905000595?token=CAD8C00992A77E092E5E0C63DC165E2B04F15005C75D56C19E72D2806079974BCF7B3ED099BE66A98ABBE1DC4D2EA01C&originRegion=eu-west-1&originCreation=20210816182907), versatile cloning sites, encoded peptide or protein tags for in-frame fusion with the gene to be expressed.

- Experimental strategies to improve expression include __variation of expression conditions, switch of the host, codon adaptation and co-expression of interacting proteins, cofactors or detoxifying systems__.


- For the __choice of  host strain__ several factors have to be considered. For instance if you want a high expression of the gene, you want to add a strong promoter. For instance one which can be transcribed by the T7 RNA polymerase. Your host strain ideally has it already encoded in its genome, otherwise you can put it on a plasmid. 

- Many expression strains are (intentionally) deficient in certain proteases which would degrade the recombinant proteins.
- Fusing the protein with an affinity tag simplifies the purification.
![[Pasted image 20210812121137.png]]


# Examples of important vectors
-   [[pET system]]
-   [[pBAD system]]
-   [[pTrc99A]]
# Host strains
Different E.coli strains can be used as host:

-   __Rosetta__ strains: Sometimes bad protein expression can be due to bad codon usage or a lack of codons in the host ([[codon bias]]). So Rosetta has some of these tRNA that are available.
-   Tuner
-   Origami

# Purification
Purification can be simplified using by attaching a tag behind the genetic sequence of your expressed protein which then can be bound by using chromatography:
- His-tags
- Strep-tags
- GST-tag

![[Pasted image 20210816213506.png]]
![[Pasted image 20210816213523.png]]


# Useful Tools for Recombinant Gene Expression
[TFinder:](https://tfinder-ipmc.streamlit.app/ ) A Python web tool for predicting Transcription Factor Binding Sites. TFinder extracts either promoter or the gene terminal regions through a simple query based on NCBI gene name or ID. It enables simultaneous analysis across five different species for an unlimited number of genes.
