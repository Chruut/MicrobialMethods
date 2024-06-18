- The pET vector has a strong __T7 (polymerase) promoter__. This gives you very high expression. 
- It's usage requires a particular strain __E.coli BL21(DE3)__, which has a chromosomal insertion of the bacteriophage __T7 polymerase gene__, which is under control of the __lac promoter__ (IPTG inducible T7 polymerase activity). 
- Basal levels of T7 RNA pol activity can be inhibited with __T7 lysozyme__ encoded on additional plasmid (pLysSor pLysE) which happens through complex formation.
- The native polymerases can't drive (= bind to) the implemented T7 promoter used in pET vectors, only the T7 RNA pol specifically can. 
- pET comprises additional copy of __lacI__ for maximal respression under non-inducing conditions (repressing the T7 pol expression). Under non-inducing conditions PT7 is repressed via binding of LacI to lacO (LacI binding site) downstream of PT7. Allows for very strong control over protein expression.

![[Pasted image 20210816210640.png]]