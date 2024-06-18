# Gene disruption
![[Pasted image 20210812084812.png]]
A plasmid bearing a region of homology is integrated at a specific site by a single cross over event which disrupts the gene intended to be mutated. The gene disruption can be selected, as the integrated plasmid retains the AB resistance cassette.

## Disadvantage
- If you have a large plasmid, it can effect the [DNA topology](https://www.youtube.com/watch?v=HyP0cEbqKTc) which could have long distance __polar effects__ (changes in downstream gene transcription levels).


# Gene (allelic) replacement
![[Pasted image 20210812084730.png]]       
The plasmid to be integrated has two regions of homology (up & down) flanking an AB resistance cassette. Its integration by a first recombination event results in a cointegrated merodiploid entity as there are two copies of the hologous regions. This is resolved by a second cross over event with two possible outcomes: (A) into the wildtype or (B) into the replacement of the gene with the plasmid DNA sandwitched between the two homologous regions (in this case AB2). The rest of the plasmid, including the other AB res cas is excised out. Thus, the allelic replacement mutant is resistant to only one of the ABs.
## Disadvantages
- A bit more complicated cloning because two homologous regions need to be cloned into
- The merodiploidy is not always easy to resolve (second recombination step). The process of resolving can be driven/assisted by constructing markerless mutants.
- If you insert a fragment which has its own promoter region, you can drive downstream genes with this promoter. Or if you have a transcriptional termination site, it could resolve in the immature termination of downstream genes (polar effects). 

## Dealing with polar effects
By inserting the [sacB](https://www.frontiersin.org/articles/10.3389/fmolb.2016.00070/full) gene these cells which have taken up the plasmid, but did not undertake the second recombination step are killed when cultivating in 10% sucrose medium. Only wt and gene deletion mutants survive. 

![[Pasted image 20210812085032.png]]

__Suicide plasmids__: Plasmids incompetent of replicating in an organism, because they lack ORI. They'll either be diluted away or get degraded after a few generations. You have to select against them, otherwise you’d just have a transformation.
__Counterselectable markers__: Promote death to the cell harboring it under certain conditions. 

To avoid the potential problems of polar effects one can use counterselectable markers to generate markerless mutants. Counterselection is used to select against merodiploidy which can be used to select a markerless deletion or wildtype strain. [sacB](https://www.frontiersin.org/articles/10.3389/fmolb.2016.00070/full) placed on a suicide plasmid can be used as a counterselectable marker. It encodes for levin sucrase which synthetizes levin from sucrose. Periplastic accumulation of levin is toxic for E. coli and any other gramnegative bacteria. The sacB gene selects for clones that have lost the vector backbone during the second HR. The genotype of the resulting clones is verified by PCR, e.g. by using the indicated primers.

 Instead of sacB, suicide plasmids may carry a dominant streptomycin-sensitive  rpsL allele as counterselectable marker. 
 
 Instead of counterselectable markers, a suicide plasmid carrying a gene encoding florescent markers (e.g. mCherry) which enable direct screening of vector-containing clones can also be used.