# A-exploration-of-the-relation-between-structure-dynamics-and-function-of-symmetrical-proteins.

This project was realized by

**Juan C Higuera C**

**Kevin N Ramos G**

This project was presented for the course **Solid State Physics** of the National University of Colombia.

Using WEBNnm@ (http://apps.cbu.uib.no/webnma3) we applied normal mode analysis for simulate dynamics for proteins, after we compare fluctuations, higher normal frecuencys and similarity between proteins with distinc simmetries and biological function. We obtain that both, simmetry of structure and biological function are related with the oscillation dynamics of the protein, but which of these are more correlated depends on whether the analysis was done before or after the alignment of the DNA sequences.

## Modeling proteins as oscillator networks
The building block of proteins are aminoacids. The aminoacids binding with peptidic edges, therefore constitutes a peptide. These peptides fold to build more complex structures, the proteins. In other words, the structure of a protein depends of the specific binding structure of peptidic edges, and this binding structure can be represented as a network.

![image](https://github.com/JuanHigueraC/A-exploration-of-the-relation-between-structure-dynamics-and-function-of-symmetrical-proteins./blob/3fd932cbf4129bd69fe03983cedabdb9d3847204/Images/aminoacid.PNG)

**Figure 1. Diagram of aminoacid.**

Take aminoacids as nodes, and peptidic edges as edges. The resulting network capture the structure of the protein. 

Once stablished a network that capture the binding structure, we can use normal mode analysis for the study of the oscillatory dynamics intrinsic in the binding structure of the protein and specifically in their simmetries.

![image](https://github.com/JuanHigueraC/A-exploration-of-the-relation-between-structure-dynamics-and-function-of-simmetric-proteins./blob/a9aba82481c0da76779be00c18f6ef129e9639e6/Images/simetries%20of%20proteins.PNG)

**Figure 2. Some simmetries of proteins.**

In this model we assume that the nodes are masses, and their edges are springs, so that the protein was modeled as a network of harmonic oscillators. 

## Simmetries and function in proteins

For this study we take two simmetries D2 and C2, and two biological functions metabolism and antigen, and select eight proteins, two for each combination of simmetry and function.

![image](https://github.com/JuanHigueraC/A-exploration-of-the-relation-between-structure-dynamics-and-function-of-simmetric-proteins./blob/c164eaf9689c6b8124ade45604df0d66749e6930/Images/tabla%20de%20proteinas.PNG)

**Figure 3. Biological function and simmetry of selected proteins.**

## Results

First we plot in order from minor to major the eigenvalues of the system.

![image](https://github.com/JuanHigueraC/A-exploration-of-the-relation-between-structure-dynamics-and-function-of-simmetric-proteins./blob/a9aba82481c0da76779be00c18f6ef129e9639e6/Images/eigenvalues%20vs%20modes%20in%20proteins.PNG)
**Figure 4. Eigenvalues of the networks oscillators.**

From this eigenvalues its posible note that for the low eigenvalues (low frecuencys) the proteins are hard to distinguish, but for fast frecuencys they organize in two groups acoording to their biological function. This suggest to us that function of proteins are related with the high frecuencys.

Therefore we align the proteins according to their similarity in DNA sequences and study their similarity in network oscillations.


### Same symmetry and same biological function.

![image](https://github.com/JuanHigueraC/A-exploration-of-the-relation-between-structure-dynamics-and-function-of-simmetric-proteins./blob/main/Images/equal%20simmetrie%20and%20equal%20function.PNG)
**Figure 5. Similarity, mean fluctuations and variance of fluctuation for proteins with same symmetry and same biological function.**



### Same symmetry distinc biological function.

![image](https://github.com/JuanHigueraC/A-exploration-of-the-relation-between-structure-dynamics-and-function-of-simmetric-proteins./blob/main/Images/equal%20simmetrie%20and%20inequal%20function.PNG)

**Figure 6. Similarity, mean fluctuations and variance of fluctuation for proteins with same symmetry and distinc biological function.**

### Distinc symmetry and same biological function.
![image](https://github.com/JuanHigueraC/A-exploration-of-the-relation-between-structure-dynamics-and-function-of-simmetric-proteins./blob/main/Images/equal%20function%20and%20inequal%20simmetrie.PNG)

**Figure 7. Similarity, mean fluctuations and variance of fluctuation for proteins with distinc symmetry and same biological function.**


### Distinc symmetry and distinc biological function
![image](https://github.com/JuanHigueraC/A-exploration-of-the-relation-between-structure-dynamics-and-function-of-simmetric-proteins./blob/main/Images/inequal%20simmetrie%20and%20inequal%20function.PNG)

**Figure 8. Similarity, mean fluctuations and variance of fluctuation for proteins with distinc symmetry and distinc biological function.**



##Conclusions 
 
**[1]** Symmetries of the protein, biological function and DNA secuences are related with the oscillatory dynamics of proteins.

**[2]** High frecuencys of the normal modes allow us distinc proteins by their biological function than that low frecuencys.

**[3]** The analysis of this work can be separated in two groups, first we calculated oscillatory properties for individual proteins and therefore compare it. Second we align the proteins and study their oscillatory properties. In the first case biological function appear as a more related propertie with oscillatory properties, in the second case was simmetrie of the proteinas that appear more related to oscillations. This suggest us that alignment are biasing the analysis because proteins that coincide in some residues in some part, will coincide in other parts because their symmetries.


