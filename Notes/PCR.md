# PCR - General
![[Pasted image 20210811215137.png]] 
- Polymerase Chain Reaction (PCR)
- PCR is a method to amplify a DNA/RNA sequence from a template. The sequence is specified by designing primers. 
- PCR is similar to in vivo cloning (recombinant DNA technology) that it is amplifying a DNA of interest. PCR is much __more efficient__, yields much more copies of DNA pieces, but much __more error prone__ with a mutation rate of 1 mutation every 1 million basepair compared to 1 in 10^10 in-vitro.
- __Primers__ should be chosen to have a similar melting temperature and selecting the annealing temperature 5-10°C below the lowest primer temperatures is recommended. For higher specificity [[#Touch down PCR]] is used
- PCR requires a thermostable [[DNA polymerases]]


# PCR techniques
## Touch down PCR
Can be used to increase specificity. There you start with a high annealing temperature (some °C higher than the melting temperatures of the primers and then it gets reduced with each cycle
 
## Overlap PCR
= Overlap Extension PCR, Splicing by Overlap Extension, etc.

![[Pasted image 20210811220111.png]]
This method is used to:
- Join two fragments 
- Introduce mutations at a specific point in a sequence. Mutations of single amino acids!
- Splice a smaller DNA fragment into a larger polynucleotide


For joining of two fragments (also called splicing) special primers are being used (here Primer B&C). These primers have a 5' overhang that's complementary to each others, so that they'll fuse. They have been generated in two separate PCR reaction beforehand. The merging is completed by another PCR reaction where only the far end primers (Primers A&D) are added. For this the sample should be purified before acting on the last step to remove primers and template strands.

To produce a mutation you would introduce it into one of the primers.

Sometimes the priming sites are not optimal, as they can form hairpins and such. But you can also alter the sequence, but there's the possibility that you affect your down-stream applications as it isn't the native sequence anymore.

## QuikChange (Stratagene) 
![[Pasted image 20210811220137.png]]
- A PCR-based site-directed mutagenesis (introduce mutations in a plasmid). 
- You can get a plasmid that has been isolated from a E.coli dam+ strain, which means it's methylated. 
- Primers with mutations are added. Mutations remain with subsequent amplification steps. There are some nicks created which can be repaired by the DNA repair machinery when introduced into E. coli.
- The methylation sites serve to get rid off the template strands as they act as restriction sites for a __DpnI__ endonuclease which recognizes methylated sites and therefore only digests the template plasmids. 
