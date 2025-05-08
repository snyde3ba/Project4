Human MDH2
P40926
T204p


## Description


Malate dehydrogenase (MDH) is an enzyme that helps transform malate into oxaloacetate, which is important for how cells make and use energy. MDH utilizes NAD+ or NADH as a cofactor to complete this reversible reaction[^1]. These enzymes are critical for aerobic metabolism, carrying out the citric acid cycle, which is necessary for transporting particles across the mitochondrial membrane and generating ATP [^2]. Mutations in MDH can become overexpressed, leading to numerous diseases, so uncovering its inhibitors is also crucial for medicine4. MDH is involved in numerous pathways, and regulatory mechanisms, which can make it more challenging to uncover which factors are crucial to its activity[^5].

1. image of the unmodified site
!Looking at the unmodified MDH2 molecule we can find it somewhat on the outside of the dimer interface. The amino acid site at 204 is found extremely close to our binding site, which is found at HIS 200. The unmodified MDH2 can be seen interacting with ASN 145, ALA 201, and GLY 199, all with hydrogen bonding. (images/aminoacidsoriginalMDH2.png)

2. image of modification site
!Evaluating the modified model, it can similarly be found on the outside of the dimer, and is interacting with the amino acids such as ASN 145, GLY 199, ALA 201, once again with hydrogen bonding. It is also still found to be close to our binding site at HIS200. Compared to the unmodified model, these are pretty similar but the modified enzyme is found to be closer to the binding site.(images/aminoacidsmodified.png)


## Effect of the sequence variant and PTM on MDH dynamics

In order to model and compare the modifications, I started with modifying their sequences and predicting their structure in AlphaFold3, as well as in Boltz-1 which helped with confirming dimer consistency. Using the .cif files from these steps, I compared the modified MDH2, the original, and the variant in Mol*. In Mol* I was able to compare the amino acids they interacted with as well as their position on the dimer. Finally after running Colab 1, I was able to remove the waters, and collect a .dcd file and a .pdb file that could be used for the Colab Step 2. The second step of the Colab providing vital information such as pKa values, RMSF, RMSD, and overall how dynamic the variant is compared to the unmodified MDH2. Again in Mol* I was able to superimpose different combinations of the three versions of MDH2 to compare their structures with one another. Overall my results from these methods were consistent, and I did not notice any significant differences between the three models. 

1. (images/superimposedunmodifiedandmimic.png) Superimposed model of unmodified MDH2 and mimic variant. RMSD 2.88

2. (images/allsuperimposed.png) All three models superimposed. RMSD 2.14

3. ! RMSD values of the mimic variant (left) compared to unmodified variant (right) produced from Step 2 Colab.
(images/rmsd_plotmod.png)(images/rmsd_plot.png)

4. Annotated plots of pKa for the key amino acids
(images/pkamimic.png)(images/pkaunmod.png)

5. If needed, show ligand bound images and how modification affects substrate binding

Description of the data and changes


## Comparison of the mimic and the authentic PTM

Compared to the unmodified model, the mimic variant the the modified model were the most different when superimposed (Figure 11). Based on the simulation data, I have learned that the T204D variant only partially mimics the effects of threonine being phosphorylated. While it still holds a negative charge at position 204, it does not have the same electrostatic strength, and hydrogen bonding that a phosphate group would have. These differences also affect flexibility, residue and possibly protein function. The RMSD value is higher than the previously superimposed, which supports my thesis that the mimic variant is largely different from the modified enzyme. I believe this value is higher because of the flexibility of the loops in the structure as well as the difference in hydrogen bonding. One introduces a negative charge to mimic phosphorylation, while the other eliminates polarity and strong bonds altogether. In figure 4, we can see the alignment of the modified and original models revealed an RMSD of 2.14 Å, which is a small deviation. The T204D side chain maintains polar bonds with a negatively charged carboxyl group, which may form hydrogen bonds or electrostatic interactions. In contrast, T204 has a hydrophobic isoleucine side chain that removes all polar functionality and introduces steric bulk (Figure 5).


(image/superimposedmimicandmodified.png)
Superimposed model of mimic variant and modified enzyme model. RMSD 4.82.



### Colab notebook links

Provide file names of completed colab notebooks



## Authors

Brooke Snyder

## Deposition Date

## License

Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg


## References

* Fermaintt, C. S., and Wacker, S. A. (2024) Malate dehydrogenase as a multi-purpose target for drug discovery. Essays in Biochemistry (Provost, J., Cornely, K., Parente, A., Peterson, C., and Springer, A., Eds.) 68, 147–160.
 ![10.1042/EBC20230081](https://doi.org/10.1042/EBC20230081)

* Minárik, P., Tomásková, N., Kollárová, M., and Antalík, M. (2002) Malate dehydrogenases--structure and function. Gen Physiol Biophys 21, 257–265.

*  Mansouri, S., Shahriari, A., Kalantar, H., Moini Zanjani, T., and Haghi Karamallah, M. (2017) Role of malate dehydrogenase in facilitating lactate dehydrogenase to support the glycolysis pathway in tumors. Biomedical Reports 6, 463–467.
![doi: 10.3892/br.2017.873]( https://doi.org/10.3892/br.2017.873)

*  Haberman, A., and Peterson, C. N. (2024) Genetics of MDH in humans. Essays in Biochemistry (Provost, J., Cornely, K., Parente, A., Peterson, C., and Springer, A., Eds.) 68, 107–119.
![DOI: 10.1042/EBC20230078](https://doi.org/10.1042/EBC20230078)

*  Martinez-Vaz, B. M., Howard, A. L., Jamburuthugoda, V. K., and Callahan, K. P. (2024) Insights into the regulation of malate dehydrogenase: inhibitors, activators, and allosteric modulation by small molecules. Essays Biochem 68, 173–181 ![10.1042/EBC20230087](https://doi.org/10.1042/EBC20230087)


