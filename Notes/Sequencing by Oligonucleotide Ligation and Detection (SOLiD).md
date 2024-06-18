- Uses ligation of fluorescently labeled DNA probes to integrate the nucleotide sequence

## Process
![[Pasted image 20210815100402.png]]
- NGS libraries are first captured on beads (one fragment per bead): A water-in-oil emulsion containing PCR reagents and one bead per droplet is created to amplify each fragment individually. Subsequently, DNA is denatured and the beads, containing one amplified DNA fragment each, are distributed onto a __glass slide__.
- Ligase-mediated sequencing begins by annealing a primer to the shared adapter sequences on each amplified fragment, and then DNA ligase is provided along with specific fluorescentlabeled octamers, which compete for ligation to the 5' end of the primer. Bases 4 and 5 are encoded by one of the four color labels. After color detection, the ligated octamer is cleaved between position 5 and 6, which removes the label, and the cycle is repeated. In the first round, the process determines bases in position 4,5; 9,10; 14,15 etc. The process is repeated, offset by one base using a shorter sequencing primer, to determine positions 3,4; 8,9; 13,14 etc., until the first base in the sequencing primer (position 0) is reached. Using this scheme each base is identified twice. 

![[Pasted image 20210815120208.png]]
_(Mardis Annual Revision Hum. Genet 2008)_

The data is collected as a series of images, identifying the beads and then followed by identification of the bead color each cycle. 

https://www.youtube.com/watch?v=nlvyF8bFDwM

## Advantages
• low error rates (99.94% accuracy (each base is read twice))
• second highest throughput system
## Disadvantages
• requires PCR amplification for library preparation
• very short reads (75 bp) -> not suited for de novo genome sequencing
• very long run times