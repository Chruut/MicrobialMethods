## Idea of Gene Set Enrichment (GSEA) and Over Representation Analysis (ORA)
- It's a functional annotation to genes by using existing pathways
- Most proteins __(for model organisms)__ have some kind of function associated, f.i. [[Gene Ontologies (GO)]], [KEGG](https://www.genome.jp/kegg-bin/show_pathway?map00010), [Webgestalt](www.webgestalt.org), Panther
- These functions are in most cases not validated with a biochemical assay but inferred from sequence homology such as BLAST
- Functions or pathways can also change or be expanded with more knowledge
- In database searches you usually have an identifier. Sometimes identifiers need to be mapped to a different identifier to be used in a downstream analysis


When doing a Differential Expression Analysis of RNA-Seq or Proteomics (PrX) data, you get data in the form of log2-fold changes, T-statistsics, p-value, etc.

You can rank the proteins according to the log2-fc and do an ORA. With a certain (lower bound) cut-off you select proteins which are up- or downregulated. And the selected proteins are submitted to the analysis where they are matched to different pathways. There is a statistical assessment for each pathway, which then comes with a p-value using contigency table and fisher exact te st. 

In the case of GSEA you don't select a cut-off, but approach it with a ranked log2-fc list. Then you check for each of your pathways, in which position of your ranked list a protein of a particular pathway. By comparing this to a random walk, you can see whether there is an enrichment of a pathway up-/downregulated.

### Wikipathways/Webgestalt analysis
![[Pasted image 20210810130627.png]]
Statistics part:
C = number of proteins within Pathway
O = number of proteins covered in experiment
E = expected number of proteins covered in the pathway by random chance
R = enrichment ratio (O/E)

![[Pasted image 20210810131017.png]]