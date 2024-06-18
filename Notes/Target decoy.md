Introduce a decoy database which has exactly the same size as your true genomic peptide database. All hits above a certain score X are accepted as a match. Then you count how many decoy hits make it into your list (labeled false positives) and you have to assume that also the same number of decoy PSMs make it in your list (not labeled). With this assumption it allows you to calculate a false discovery rate (FDR). The bigger the FDR, the more of the decoy database you have let slip in, which means it is a bad model. If the FDR is too high, this probably means that your threshhold was too low or you have selected the wrong database. 

## Calculating the False Discovery Rate
This serves as a confidence measure! 
![[Pasted image 20210809214348.png]]

You have to assume that 20 out of your 980 identifications are potentially False Positives. 20/980 = 2.04% False Discovery Rate

### Necessary assumptions
Two assumptions have to be met for the Target Decoy approach to hold:
1. Target and decoy databases do not overlap and their distributions are the same. 
![[Pasted image 20210810104728.png]]
They share the same distribution.
For peptides longer than 7 aa it's extremely unlikely that it is present in the target and decoy database at the same time
2. It's equally likely for targets and decoys to get a false positive 
![[Pasted image 20210810105125.png]]
rank 1 = best score
a) On rank 1 it is clear that we should have a higher probability that it is the decoy. But from rank 2 onwards, target and decoy should be around 50/50
b) To show what happens when you shift the precursor. This is the result that you get if you tell the program that the precursor was 10 Da more than it actually is. You'll always end up in the wrong candidate space and make wrong identifications. Also for rank 1 it's a 50/50 chance. 


