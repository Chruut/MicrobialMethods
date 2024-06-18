==Parameters that can be distinguished using flow cytometry:==   

used to measure and analyze the physical and chemical characteristics of cells or particles as they flow in a fluid stream through a beam of light, typically a laser. Some of its primary applications are:
- Cell counting and sorting
- 

# General
- __Flow cytometry__ is an analytical method to measure and quantify multiple parameters of a large number of cells in a heterogenous sample on the single cell level on many samples, relatively quickly.
- __FACS__ is for cell sorting


Alternative would be [[Western Blot]]:

The advantage of WB is that several samples can be analysed simultaneously and you can use a large number of cells for the evaluation. The required equipment is also relatively inexpensive.

Big disadvantage of WB is that you can only look at one parameter at the time and that multiple cells have to be lysed and homogenised. So the readout is averaged and not on the single cell level. It's also rather slow.

The data is then given in the following form:

![[Pasted image 20210816094232.png]]

A table with the different parameters (A-D) measured and the relative abundance of each cell type.

## Prerequisites for Flow Cytometry

- Single cell/particle suspension (no intact solid tissues, no clusters, no aggregates)
- Most cellular parameters (other than paramters like complexity or granularity or external vs. internal refraction index) have to be revealed through sample preparation, in order to be seen, although particles/cells per se are “visible” to the cytometer without staining/reporter/etc. 

Parameters are __made visible__ by:
- labelling with fluorochrome-labelled antibodies or DNA probes ([[Fluorescent in situ Hybridisation (FISH)]])
- dye labelling for organelles or non-specific cellular dyes
- fluorescent reporter [[Fluorescent Reporters]] (e.g. GFP expression of the promoter of choice)

## Advantages of Flow Cytometry:
- Multi-parameter analysis: up to ~20 parameters
- Single cell assay ⇒ Data is not overall average of sample but every parameter is measured for every cell/particle in sample (averaging easily possible).
- Single cell assay ⇒ The resolution is identical for extremely rare or very abundant cells/particles. It is thus largely irrelevant whether the cells/particles in question are abundant or rare within the sample. The quality of the data will be similar
- Single cell assay ⇒ Hetergenous cell mixtures can be analysed in detail.
- Large number of cells/particles can be interrogated: From 1 to millions of cells/particles per sample.
- Quantification is easily possible (however generally not absolute but relative)
- Large number of samples can be analysed: From 1 to hundreds of samples (optional: automated, robot controlled)
- Data can easily be filtered at will through “gating” based on parameter criteria
- Extensive statistical data analysis on the level of events (cells/particles) or samples possible


## Disadvantages

• No information on subcellular localisation in cell with respect to measured parameter. Only association of a certain expression level with an “event”.

• No information on tissue architecture/organisation (single cell suspension required)

• No (absolute) information on the shape/morphology of the cell/particle. Exception: imaging cytometers.

• No simultaneous measurement of samples

• Analytic cytometers: Cell can only be interrogated 1×

• Information is only a __snapshot__ of a cell’s parameters at a given time, no kinetic analysis of individual cells possible. After measurement the cells are collected in a trash bin

• In general, parameter values are relative, not absolute
--> __Comparators (references) are crucial!__

• Costly equipment required

## Applications

- Phenotype analysis (cell surface antigens/markers) wo see which cell types are in your sample (f.i. markers for CD4 --> T-cells)
- Intracellular analysis: e.g. cytokines, transcription factors, signal transduction (e.g. by using antibodies specific for phosphorylated forms of molecules), phagocytosed bacteria and particles, etc.
- DNA analysis: cell viability (distinguish living from dead cells using membrane impermeable dyes f.i. propidium iodide (PI)), current stage in cell cycle, apoptosis (using Annexin V), etc.
- Cell function analysis: e.g. free radicals, cell signaling with [[ratiometric dyes]] (Calcium flux), pH, reporter genes, etc. (only a snapshot)
- __CBA (Cytometric Bead Array)__: Measurement of the concentration of soluble molecules. Usually flow cytometry only can measure particulate samples), so the analyte has to be adsorbed on particles, because 
- Measurement of __proliferation__: 
1)[[Bromodeoxyuridine (BrdU)]]  
2)[[CFSE staining]] 
## Working principle
### Sample preparation
Example: Identifying T-cells in blood through specific antigens

1. Start with whole blood sample (no cell sieve or digestion necessary in this case)
2. Ficoll gradient for blood cell separation from plasma
3. Stimulation with antigen
4. Brefeldin A to inhibit cytokine expression
5. Surface staining for CD4/CD3, which identifies T-cells
6. Washing and fixation
7. Lysation of RBCs
8. Flow cytometer analysis

## Data analysis
Data is typically displayed as dot plots, contour plots (not always helpful) or pseudo-density plots (indicates quantity in an area). Each dot resembles an event and the axis are parameter quantifications:
![[Pasted image 20210816110546.png]]

Light scatter occurs when the cell deflects laser light:
- Forward scatter: Determined by the external refraction index vs. internal one (how big is the nucleus compared to the whole cell)
- Sidescatter: determined by granularity/complexity

![[Pasted image 20210816110305.png]]
Based on scatter, cell debris and other artifacts (dots close to the origin) can be filtered out (= __scatter gate__). 

This can then be followed by plotting according to identification paramters. In this case CD4 identifies T-cells and DX5 identifies NK cells. It can also be displayed in a histogram (for multiple cell types if you want) to show the percentage of cells which express the phenotype. Theres always a threshold which separates significant detection from baseline noise levels. 
![[Pasted image 20210816112334.png]]
# FACSorting

## Applications
- Separation of complex/heterogeneous cell preparations for biochemical analysis.
- As above, for functional in vitro or in vivo assays were pure cell preparations are required.
- Sorting e.g. of transgenic T cells for transfer into host animals (high purity)
- Sorting of individual cells (e.g. into 96- or 384-well plates) for cloning, single cell techniques (e.g. RNA-seq).
- etc.

- Special commercial application: Sperm sexing (large-scale farm animals): Bulls dont give milk --> Artificial insamination, total DNA content of “female” and “male” sperm differs using DNA-intercalating dye (mutations possible if not properly washed out!)

# Mass Cytometry
Using heavy metal isotopes on ABs for labeling instead of fluorescent dyes for up to 50 different markers. Analyzed by MS in contrary to optics. Expensive, but is becoming more available.

## Disadvantages
You can't sort cells, because the cells are destroyed. Further, experiments with 30 and more different parameters are impossible to be analyzed manually. New approaches to data analysis are needed. 

# Imaging cytometry
Combination between microscopy and flow cytometry. For every event the machine also takes a picture. You get the statistical power of flow cytometry and in addition can get morphologic information and can give information about co-localization of the different factors. Up to 2000 events/sec (with 10 measured parameters) together with 60x magnification pictures is possible. The quality of those pictures is not great however, can't compete with a standalone confocal microscope.



**ToDO: ifferent ways of detecting the different "aspects" like cell cycle.
Isotope elements**

