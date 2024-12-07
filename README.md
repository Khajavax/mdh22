# Human Mitochondrial MDH2

# Uniprot ID: P40926
# Variation: phosphorylation of T73 (pT49 in structure)



## Description

Threonine 73 of Human MDH2......... was identified as a post-translationally modified site by [Reinders and coworkers](https://pubmed.ncbi.nlm.nih.gov/17761666/) in 2007. The study identified proteins with a role in the assembly of ATP synthase and energy metabolism.  This modification site is not conserved in human MDH2 [(P40926)](https://www.uniprot.org/uniprotkb/P40926/entry) 
and there are no functional studies of the role of this site in yeast metabolism. 
*Entry started 10/21/2024 CEB*

# Comparison of MDH2 models and phospho modified MDH2

1. Alignment of MDH2(Yellow), MDH2 with phosphoT 73(Red), and T73D(Blue)
<img width="800" alt="align" src="https://github.com/user-attachments/assets/2b341f32-4d44-43d8-bd29-752a12ffd125">



2. Representation of Active(pink), Binding(green), and Modification(yellow, red, blue) sites on MDH2
![alt text]<img width="367" alt="Screenshot 2024-12-06 at 10 33 25 PM" src="https://github.com/user-attachments/assets/352f6006-c2e7-4b64-9eea-47de8751f01a">
(/site.png)

The modification site is near to R174 and E178 and could make ionic or hydrogen bonding interactions with both of those side chains when modified. 

3. Comparison of amino acid 73 weak interactions with surrounding amino acids in Original (yellow), phosphoT73 (red), and mimic T73D(blue)
![alt text](images/si<img width="608" alt="Screenshot 2024-12-06 at 10 34 19 PM" src="https://github.com/user-attachments/assets/ab4f4312-bf46-41f0-ac9e-9551384dea09">
te.png)


## Effect of the sequence variant and PTM on MDH dynamics

 Comparison of post-MD simulations of original MDH2(yellow) and mimic T73D MDH2(blue) is <img width="261" alt="Screenshot 2024-12-06 at 10 37 03 PM" src="https://github.com/user-attachments/assets/68f27407-de2b-4541-ad59-6fb52cfd7068">
Comparison of post-MD simulations of original MDH2(yellow) and mimic T73D MDH2(blue)


After simulation, the overall protein structures are similar as well as the area surrounding the modification sites. A solvent sodium ion has moved close and is forming an ionic interaction with the D in position 177. D177 also is making contact with R174. Neither of these interactions are observed in the unmodified enzyme.
<img width="388" alt="Screenshot 2024-12-06 at 10 40 38 PM" src="https://github.com/user-attachments/assets/a8bd55b2-a94d-41b5-b635-b08e2224676d">
 Comparison of modification sites on post-MD simulations of original MDH2(yellow) and mimic T73D MDH2(blue)
![alt text](images/md_site.png)

### Comparison of the enzyme dynamics
After simulation, the dynamics as described by the root mean square fluctuation (RMSF) value were compared. In the plot, there are differences between the unmodified (purple) and S177D (green) around amino acids 400 and 500. These sites are loops bordering the active site. The difference around residue 400 is the active site loop which is key for binding the carboxylic acid substrate. The vertical line indicates the end of one subunit and the beginning of the next subunit of the MDH1 dimer.

<img width="434" alt="Screenshot 2024-12-06 at 10 42 04 PM" src="https://github.com/user-attachments/assets/ce2e11fc-0685-474b-b59f-c8bf7d68621a">
Overlapping Comparison of RMSF values in Angstroms (y-axis) for each amino acid position (x-axis) for MD simulations of original MDH2(yellow) and mimic T73D MDH2(blue)

### Effect of modification on the pKa values

Overall the modification did not affect the pKa values of the active site histidine. There are only minor differences in the spread of the data over the simulation which may be due to equilibration. 
<img width="434" alt="Screenshot 2024-12-06 at 10 43 10 PM" src="https://github.com/user-attachments/assets/851585f1-7a9d-4dad-98ab-d6ff0c507610">
pKa fluctuation for Histidine 200(176 in structure)(active site) for MD simulations of original MDH2(yellow) and mimic T73D MDH2(blue)

## Comparison of the mimic and the authentic PTM
The RMSD MDHS177D and phosphoS177 MDH1 was 0.48 Å. The overall structures are similar with no major differences in structure or position.

<img width="274" alt="Screenshot 2024-12-06 at 10 43 58 PM" src="https://github.com/user-attachments/assets/5f33d250-84de-4e6a-80b5-40dfb19460e7">
Alignment of the MDH2 with phosphoT 73(red), MDH2 mimic T73D(blue).

## Colab notebook links





## Authors

Ali Khajavi

## Deposition Date
12/06/2024

## License

Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg

## References

(1) UniProt. https://www.uniprot.org/uniprotkb/P40926/entry (accessed 2024-12-06).
(2) AlphaFold Server. https://alphafoldserver.com/ (accessed 2024-12-06).
(3) Sehnal, D.; Bittrich, S.; Deshpande, M.; Svobodová, R.; Berka, K.; Bazgier, V.; Velankar, S.; Burley, S. K.; Koča, J.; Rose, A. S. Mol* Viewer: Modern Web App for 3D Visualization and Analysis of Large Biomolecular Structures. Nucleic Acids Research 2021, 49 (W1), W431–W437. https://doi.org/10.1093/nar/gkab314.
