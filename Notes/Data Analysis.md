

After the aquisition of the data we have to identify which peptides belong to which proteins. Certain programs allow us to calculate the probabilities and adjust the fragment masses to theoretical masses. Asssignment score! 
Schmidt et al 2015

## LC-MS
Peptide mixture bound to an RP-column is continuously eluted with a gradient of Solvent A (aqueous) to solvent B (organic) to be registered by the MS analyser
![[Pasted image 20210809210904.png]]

x-axis = m/z; y-axis = retention time

For each point on the y-axis you get the features which got eluted at the same time and therefore get analyzed at the same time (f.i. TOF). The result of the mass analysis is given on the x-axis.
### Data-dependent Acquisition (DDA)
One full scan (parent scan), followed by X data-dependend scans. Which precursor analytes are selected, depend on the intensity of precursor analytes. These then undergo a MS/MS analysis, which allows for a very accurate identification of what is eluting at the moment.  
![[Pasted image 20210809210946.png]]

## Assessing structural information
Data combined:
- Precursor mass for each MS/MS spectra
- Elution time
- Charge
- Scan number

Simultaneously to the wet lab process in the MS, you create a theoretical spectrum based on the genome sequence. You create theoretical protein sequences from which in silico tryptic peptides are derived. Given the tandem fractionation technique used you finally generate a library of possible fragments. Then a scoring algorithm scores the spectra derived in these two ways __(Peptide Spectrum Match, PSM)__ wich results in peptide identification. 

### Considerations
- It's important to have the proper database selected, as sequence errors will lead to no identification
- For unsequenced organisms, the chance of identifying a peptide is only possible on the basis of completely identical peptides
- Search time is affected by the precursor mass accuracy, which defines the space of potential theoretical peptides


## Validation
PSM is a question of probabilities, eventhough generally a PSM will result in one "best hit". There are several biostatistical methods for this decision:
- [[Target decoy]]

## Protein inference
peptide --> protein identification
![[Pasted image 20210810113702.png]]
Identified peptides which are not unambiguous would still identify the MAPK protein, but there might be multiple possible proteins which produce these peptides. 
### FDR vs. FPR and upscaling to the protein level
False Discovery Rate (FDR): FDR = 5% means that among all the features called significant, on average 5% of these are truly _null_.

False Positive Rate (FPR): FPR = 5% means that on average 5% of the truly null features in the study will be called significant. 

![[Pasted image 20210810112103.png]]
We are only interested in the FDR!

Not every MSMS spectra (PSM) correlates with an individual new peptide, because the same peptide can be registered as doubly charged, tripple charged or is just measured more than once. This means that the FDR is higher on the peptide level than at PSM and the same happens if you go on the protein level. 

![[Pasted image 20210810113040.png]]

## Practice
- Contaminants: Proteins such as Trypsin and skin proteins which can fall off from the researcher can always end up in your measurements. This is why a list of contaminants always has to be added. 
- Don't over-estimate the number of identified proteins. If there is an peptide which links to three different proteins, it's not correct to add all 3 proteins.  
- For quantitative approaches, shared peptides should be discarded or treated separately. 


## Applications
- The comparison of multiple lists coming from the same cells under different conditions or cells from different tissues allows to make statements about particular biological processes happening within the cell
- Functional categorization: [[Gene Set Enrichment Analysis (GSEA) & Over-Representation Analysis (ORA)]] can give innsights on dominant biological processes
- Projection of identified proteins on pathways of metabolic maps to visualize certain ongoing processes [biocyc pages](https://yeast.biocyc.org)
- Infer Protein Networks [string](www.string-db.org) and complex formation from resources which document protein-protein interaction. Possible interactions: regulation, PTM, physical interaction


