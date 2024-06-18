Digestion/fractionation is an important aspect of Sample Preparation which helps coping with the complex mixture of proteins within the sample.

## Protein Fractionation
### Gel-based fractionation
- [[1D fractionation]]
- [[2D fractionation]]
These two generally are very useful for sample clean ups (f.i. detergents)
But membrane proteins generally don't tend to drive well in gels.
- [[Off-Gel Electrophoresis (OGE)]]

### Liquid Chromatography Techniques
More often used in high-throughput shotgun proteomics than gel-based techniques

![[Pasted image 20210809172516.png]]

Different techniques:
- Reverse phase (RP-C18 resin): Good peak capacity, uses hydrophobic stationary phase (alkyl groups)
- Hydophilic Interaction Chromatography (HILIC): Good peak capacity
- High vs. low pH
- Strong cation exchange (SCX): bad peak capacity
- Size exclusion chromatography: bad peak capacity


The different techniques can be combined to a 2D separation, while the low pH RP-HPLC is typically used as second dimension, directly coupled to the MS. 
![[Pasted image 20210809173501.png]]
_Gilar M. et al (2005)_

 ## Protein Digestion
 Protein digest is important because the biophysical properties (ionization properties and masses) of proteins are much too diverse to separate them with the available LC-resins. Mass analyzers also have difficulties measuring a broad range of analytes. 
 
 ### Enzymes used
 ![[Pasted image 20210809174034.png]]
 "N or C term" refers to on which side of the peptides it cleaves
 
 
 ![[Pasted image 20210809174256.png]]
Protein sequences with all the residues marked that could be cleaved. 

Other enzymes/chemicals (like CNBr) can be used to create differen sizes, which can be used to find a complete sequence for the protein, or to get a different coverage. And sometimes if there are certain PTMs, Trypsin is unable to cleave it. The disadvantage of big peptides is that their prediction rate is low (more possible compositional combinations)

Otherwise __Trypsin__ is most often used, because: 
- It cleaves specifically
- Its cleavage site is equally distributed in all proteins
- The length of the produced peptides are in a nice medium mass range of MS
- Since K and T can bind a charge on their C-terminals, Trypsin stabilizes a positive charge

![[Pasted image 20210809175123.png]]

Protein digestion makes the analysis more complex which is reduced by sample fractionation prior to digestion.

