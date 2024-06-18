 A neutral method to describe a populations structure where the change in bacterial composition as a result of bottleneck events and a set of genetic tags within a population is used. 
 In principle, this approach employs the principle of [genetic drift](https://en.wikipedia.org/wiki/Genetic_drift) (bottleneck), which is the reduction in population diversity or also the founding of a new, spatially separated population by a low number of founder organisms. Genetic drift is particularly pronounced in small populations.

 ## Process
 ![[Pasted image 20210804155941.png]]
 The figure illustrates a scenario in which the same starting population of cells with equal fitness in a given system undergoes one contraction and two expansion events in a different order, and how this affects population structure. One can see that diversity is maintained during expansion and is reduced by contraction. The timing of these event effect the final composition of the bacteria. Notably, the number of cells at the biggining and the end are the same and the two scenarios would be indistinguishable by conventional methods of cell counting. 
 
 For each separate stage within the observed process the following is done: 
 1) The sample is plated out to estimate total bacterial CFU
 2) CFU/genetic tag the different colonies are then idenfied via [[Quantitative real-time PCR (qRT-PCR)|qPCR]] or [[NGS]] (better) to determine the diversity and poopulation composition (frequency changes over time). 
 3) Together with mathematical modeling a quantification of dynamic parameters (growth rate, migration rate etc. ) predictions of population composition can be made.
 

 ## Applications
 - Can be used to assess other dynamic parameters (growth rate, death rate, bottleneck sizes, migration rates etc.). Well characterized systems allow the setup of mechanistic multi-compartement models to describe dynamic changes. With that, the population size at timepoint t can be predicted. Having a working model you can use it to predict the behavior of your population if certain parameters of the infection change (for instance if you have a treatment that will change the migration rate from intenstine to lymph nodes, you can predict the outcome for the population size in the spleen)
 - The same principles for modeling bacterial populations can be applied to __host responses__ (host cell populations dynamics) and to analyze the __behavior of fungi__. 
 - The method can be utilized as a means of quality control for experiments analysing the __competitive index (CI)__ of bacterial mutants, which is the ratio of mutants to wild-type cells in a sample. 
 
 
 - Example: In order to assess the differentiation into different subsets, T cells can be extracted from a mouse to labeld them with a barcode using a retrovirus construct and then put back into the mouse. 
![[Pasted image 20210804164809.png]]



 ## Advantages
 - Truly Fitness neutral --> no skew in the population dynamics
 - A large variety of different barcodes can be introduced into the population
 - Fast identification of barcodes via NGS (better than qPCR where you can't analyze hundrets of tags at the same time) 

### Methods of generating tags
 - Wild-type Isogenic Tagged Strains __(WITS)__ --> 7-8 tags (Grant et al. 2008): 40bp DNA signature tag in the same noncoding region of the chromosome with no interstrain difference in growth rates 
 - Sequence Tag-based analysis of microbial populations (STAMP) --> hundrets of tags (Abel et al. 2015) created by isothermal DNA assembly ([[Gibson assembly]])
 