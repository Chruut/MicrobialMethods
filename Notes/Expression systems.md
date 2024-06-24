Recombinant expression systems enable the production of proteins that are difficult or impossible to obtain from natural sources by introducing a gene of interest into a host cell. They provide essential tools for scientific research, medical therapies and industrial applications.

# General Process in Recombinant Expression of Functional Genes
Recombinant expression of functional genes in organisms like yeast or E. coli involves several key steps:

1. Gene Identification and Isolation: Identify and isolate the gene of interest. This can be done using PCR (polymerase chain reaction) to amplify the specific gene from the source DNA.

 2. Cloning the Gene: Insert the isolated gene into a plasmid vector. The plasmid is a small, circular piece of DNA that can replicate independently within a host cell. This process often involves:
      - Cutting both the plasmid and the gene with specific restriction enzymes to create compatible ends.
      - Ligation of the gene into the plasmid using DNA ligase.

3. Transformation: Introduce the recombinant plasmid into the host organism (e.g., E. coli or yeast). This can be achieved through methods such as heat shock or electroporation, which temporarily make the host cell membrane permeable to DNA.

4. Selection: Select for successfully transformed cells. The plasmid vector typically contains a selectable marker, such as an antibiotic resistance gene, which allows only the transformed cells to grow in the presence of the antibiotic.

5. Expression: Induce the expression of the gene in the host organism. The plasmid is designed with regulatory elements like promoters, which control when and how much of the gene is expressed. Induction can be triggered by adding specific chemicals or changing environmental conditions.

6.  Protein Production and Purification: Once expressed, the protein product can be isolated and purified from the host cells. This may involve lysing the cells to release the protein, followed by purification steps such as affinity chromatography, which isolates the protein based on specific binding properties.

7.  Verification: Confirm the expression and functionality of the recombinant protein through various analytical methods, such as SDS-PAGE, Western blotting, or functional assays.

This process allows for the production of large quantities of a specific protein for research, industrial, or therapeutic purposes.

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

-   __Rosetta__: The *E. coli* Rosetta strain contains additional tRNA genes for rare codons (such as AGG, AGA, AUA, CUA, CCC, and GGA), which improves the translation efficiency of eukaryotic proteins ([[codon bias]]). 
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
