### Multiplexed proteomics (isobaric tags)
 As __Multiplexed proteomics__ are proteomic methods refered to which use isobaric tags to analyze multiple protein samples.
 
_Nishant Pappireddi, M Wühr 2019:
Label-free quantification provides comparatively poor precision regarding quantitative measurements. Additionally, missing values of peptides that are only identified in some samples are hard to interpret even qualitatively. DIA mostly overcomes the missing value problem of the DDA approach but samples are still analyzed one at a time, limiting measurement precision and requiring lots of instrument time. While MS1-based isotope labeling offers exquisite quantification for more abundant peptides, it suffers from a lack of multiplexing capability, because, as the number of samples increases, so does the complexity of the MS1 spectrum. _

Multiplexed proteomics, based on isobaric mass tags, promises to overcome or at least mitigate these limitations. The most commonly used isobaric tags are [TMT](https://www.wikiwand.com/en/Tandem_mass_tag) and [iTRAQ](https://www.sciencedirect.com/science/article/pii/S153594762032939X?via%3Dihub). Sample multiplexing for quantitative proteomics __enables improved precision, reduced missing values, and increased throughput.__

![[Bildschirmfoto 2021-08-10 um 16.31.50.png]]

A) __Isobaric tags__ are reagents used to covalently modify peptides, using the heavy isotope distribution in the tag to encode the different conditions. They are generally added after digestion. Isobaric tags have the same total mass, but differing distributions of heavy isotopes between the __reporter group__ and __mass balancer__ (Heavy isotopes are shown as asterisks). The four identical peptides from different samples elute at the same time and therefore appear as a single peak in the MS1 spectrum, which can be isolated. With more tags (conditions), the complexity of the MS1 spectrum does not increase. This makes isobaric tags compatible with higher multiplexing (__currently up to 11__) compared to e.g., SILAC. In addition to the reactive group, which reacts with the peptide, each tag contains a reporter group with differential number of heavy isotopes. 

B) Quantification occurs after isolation and fragmentation of these labeled peptides in the MS2 spectrum. Usually, the amount of energy added for fragmentation is only enough for one bond to break. This could either be a peptide bond on the backbone or the intended breakage point in the isobaric tag. The reporter ions show different masses in the MS2 spectrum and can be used for relative quantification. Additionally, the breakage of the isobaric tag leads to the formation of complementary reporter ions, which contain the balancing part of the isobaric tag and the intact peptide or fragment ions, which result from breakage in the peptide backbone and the isobaric tag. The complementary reporter ions can also be used for quantification. __The b- and y-ions are used for peptide identification.__

__Absolute quantification__ of targeted proteins can be achieved by using synthetic peptides tagged with one of the members of the multiplex tags.

#### Tag attachment
All isobaric tags contain a functional group that enables covalent attachment to peptides. Typically, this group reacts with primary amines on a peptide’s __N-terminus or lysine sidechains__, as is the case here. However, some tags react with carbonyl or sulfhydryl groups.

The protein sample can be analyzed globally with the aim of identifying and quantifying as many proteins as possible, or one can also focus on peptides of certain selected elution times for a few proteins of interest. This enables analysis of much less abundant peptides!

#### Challenges
__Interference__: WIth current mass filters peptides rarely get isolated perfectly. In complex mixtures, whenever a peptide is isolated in the MS1 spectrum for MS2 analysis, other peptides with similar m/z values will nearly always be co-isolated. Nearly all measurements are therefore distorted, often to a significant extent and the less abundant the target peptide, the bigger the relative interference. In general, these contaminating ions tend to bias the relative __ratios between different conditions__ towards a 1:1 ratio. For some studies, the __qualitative__ knowledge on which proteins change is sufficient. However, if one is interested in the __quantitative__ change of protein expression levels, addressing interference is essential. The issue of interference is best overcome by experimental measures such as  
__Gas-phase purification (Quantmode, MS3)__ or the __Complement Reporter Ion-Based Approach (TMTc)__, secondary fragmentation of TMT containing ions followed by MS3 scan.

- [[Ion suppression]] has a detrimental effect on accuracy of abundance measurements in large studies which require the use of multiple batches. 

https://www.mcponline.org/article/S1535-9476(20)32939-X/pdf