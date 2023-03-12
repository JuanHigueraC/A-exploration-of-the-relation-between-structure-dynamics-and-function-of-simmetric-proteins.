# A-exploration-of-the-relation-between-structure-dynamics-and-function-of-symmetrical-proteins.

This project was realized by

**Juan C Higuera C**

**Kevin N Ramos G**

This project was presented for the course **Solid State Physics** of the National University of Colombia.

Using WEBNnm@ (http://apps.cbu.uib.no/webnma3) we applied normal mode analysis for simulate dynamics of proteins, after we compare fluctuations, higher normal frecuencys and similarity between proteins with different symmetries and biological function. We obtain that both, symmetry of structure and biological function are related with the oscillation dynamics of the protein, but which of these are more correlated depends on whether the analysis was done before or after the alignment of the DNA sequences.

## Modeling proteins as oscillator networks

The basic component of proteins are aminoacids. Aminoacids are linked to each other by peptide bonds, in such a way that they form peptides. These peptides fold to build more complex structures, proteins. In other words, the structure of a protein depends on the specific binding structure of peptide bonds, and this binding structure can be represented as a network.

![image](https://github.com/JuanHigueraC/A-exploration-of-the-relation-between-structure-dynamics-and-function-of-symmetrical-proteins./blob/3fd932cbf4129bd69fe03983cedabdb9d3847204/Images/aminoacid.PNG)

**Figure 1. Diagram of aminoacid.**

Take aminoacids as nodes, and peptidic edges as edges. The resulting network capture the structure of the protein. 

Once a network that captures the linkage structure has been established, we can use normal mode analysis to study the intrinsic oscillatory dynamics in the protein's linkage structure and specifically in its symmetries.

![image](https://github.com/JuanHigueraC/A-exploration-of-the-relation-between-structure-dynamics-and-function-of-simmetric-proteins./blob/a9aba82481c0da76779be00c18f6ef129e9639e6/Images/simetries%20of%20proteins.PNG)

**Figure 2. Some symmetries of proteins.**

In this model we assume that the nodes are masses, and their edges are springs, so that the protein was modeled as a network of harmonic oscillators. The equation that gobern the dynamics was:

$$ \frac{1}{2}\textbf{M} \frac{d^2 \eta_i}{dt^2} +   \frac{1}{2}\eta_i V_{ij}\eta_j = 0$$

where $\textbf{M}$ was a diagonal matrix that contain the masses and $V_{ij}$ was a matrix that captures the binding structure of the protein with cuadratic potentials. The solution of this systems of equations are:

$$ \eta_i = a_{ij}cos(w_kt + \delta_k) $$ 

## Symmetries and function in proteins

For this study we took two symmetries D2 and C2, and two biological functions metabolism and antigen, and we selected eight proteins, two for each combination of symmetry and function.

![image](https://github.com/JuanHigueraC/A-exploration-of-the-relation-between-structure-dynamics-and-function-of-simmetric-proteins./blob/c164eaf9689c6b8124ade45604df0d66749e6930/Images/tabla%20de%20proteinas.PNG)

**Figure 3. Biological function and symmetry of selected proteins.**

## Results

First we plot in order from minor to major the eigenvalues of the system.

![image](https://github.com/JuanHigueraC/A-exploration-of-the-relation-between-structure-dynamics-and-function-of-simmetric-proteins./blob/a9aba82481c0da76779be00c18f6ef129e9639e6/Images/eigenvalues%20vs%20modes%20in%20proteins.PNG)
**Figure 4. Eigenvalues of the networks oscillators.**

From this eigenvalues its posible note that for the low eigenvalues (low frecuencys) the proteins are hard to distinguish, but for fast frecuencys they organize in two groups acoording to their biological function. This suggest to us that function of proteins are related with the high frecuencys.

Next we align the proteins according to their similarity in DNA sequences and study their similarity in network oscillations.


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



## Conclusions

 
**[1]** Symmetries of the protein, biological function and DNA secuences are related with the oscillatory dynamics of proteins.

**[2]** High frecuencys of the normal modes allow us distinc proteins by their biological function than that low frecuencys.

**[3]** The analysis of this work can be separated into two groups, first we calculated the oscillatory properties of individual proteins and thus compared them. Second, we align the proteins and study their oscillatory properties. In the first case the biological function appears as a property more related to the oscillations than the symmetry, in the second case it is the symmetry of the proteins that appears more related to the oscillations. This suggests to us that the alignment is biasing the analysis, which may be because proteins that match some residues somewhere will match elsewhere due to their symmetries.


