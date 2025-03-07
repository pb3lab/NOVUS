# NOVUS LA TRIADA
## Repositorio abierto de laboratorios prácticos computacionales en la nube para educación STEM

Este repositorio cuenta con distintos cuadernos de Jupyter con instrucciones y código de Bash y Python para la ejecución de laboratorios prácticos en distintas disciplinas utilizando [Google Colaboratory](https://colab.research.google.com/?hl=es), un servicio alojado en la nube que no requiere configuración y que ofrece acceso gratuito a recursos de computación, incluyendo CPUs, GPUs y TPUs.

Cada cuaderno de Jupyter consiste de un laboratorio práctico con instrucciones de las actividades a realizar, la instalación de *software* adicional a utilizar para cada laboratorio, y distintas celdas de texto y de código en Bash y Python para ejecutar tareas de cómputo, análisis y visualización de datos. Además, todos los laboratorios prácticos se encuentran disponibles tanto en español como en inglés.

## Laboratorios de Modelado y Simulación Molecular

<table>
<thead>
<tr>
<th style="width: 15%;">Tutorial</th>
<th style="width: 30%;">Descripción</th>
<th style="width: 20%;">Versión en español</th>
<th style="width: 20%;">Versión en inglés</th>
<th style="width: 15%;">Software Adicional</th>
</tr>
</thead>
<tbody>
<tr>
<td>Lab.01</td>
<td>Uso de Colab y Revisión de Bases de Datos de Biomoléculas</td>
<td><a href="https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutoriales/ModSimMol/lab01_intro.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" width="120"/></a></td>
<td><a href="https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutorials/ModSimMol/lab01_intro.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" width="120"/></a></td>
<td>
</td>
</tr>
<tr>
<td>Lab.02</td>
<td>Visualizando y Comparando Estructuras Moleculares en Google Colab usando py3Dmol</td>
<td><a href="https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutoriales/ModSimMol/lab02_molviz.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" width="120"/></a></td>
<td><a href="https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutorials/ModSimMol/lab02_molviz.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" width="120"/></a></td>
<td>Biopython [4], py3Dmol [5], NGL Viewer [6]
</td>
</tr>
</tbody>
</table>


                                                         |

## Tutorials – 2021 & 2023

The following is a brief description of each tutorial generated in 2021 & 2023, along with the open-source software used for each task:

| Tutorial | Description                           | Software                                                        |
|--------|-------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|
| Lab.13 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/ibm3202/blob/master/tutorials/2021/lab13_protDCASBM.ipynb) | Combining DCA and SBM to predict protein structures | SMOG2, SBM-enhanced GROMACS [3], Biopython [4], py3Dmol [5], pyDCA [18]                          |
| Lab.14 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/ibm3202/blob/master/tutorials/2023/lab14_MSAtransformer.ipynb) | Combining MSA Transformer and SBM to predict protein structures | SMOG2, SBM-enhanced GROMACS [3], Biopython [4], py3Dmol [5], MSA Transformer                          |


## Tutorial for Structural Biology in 2022


| Tutorial | Description                           | Software                                                        |
|--------|-------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|
| Lab.15 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/ibm3202/blob/master/tutorials/2022/lab15_CF-GROMACS.ipynb) | Combining ColabFold and GROMACS to predict and simulate protein structures | GROMACS [2], Biopython [4], py3Dmol [5], NGL Viewer [6], ColabFold [19]      |


## Authors
Felipe Engelberger, Pablo Galaz-Davison, Graciela Bravo, Maira Rivera and César A. Ramírez Sarmiento.

**Protein Biophysics, Biochemistry and Bioinformatics Lab [(PB<sup>3</sup>)](https://pb3.sitios.ing.uc.cl)**, Institute for Biological and Medical Engineering (IIBM) / Millenium Institute for Integrative Biology (iBio)

## Cite us!

If you use these tutorials in your research/teaching, please **cite us!:**

Engelberger F, Galaz-Davison P, Bravo G, Rivera M, Ramírez-Sarmiento CA (2021) Developing and Implementing Cloud-Based Tutorials that Combine Bioinformatics Software, Interactive Coding and Visualization Exercises for Distance Learning on Structural Bioinformatics. _J Chem Educ 98_(5): 1801-1807. **doi:** [10.1021/acs.jchemed.1c00022](https://dx.doi.org/10.1021/acs.jchemed.1c00022)

## Contributions and Code of Conduct

Please **read** our rules on [Contributions and Code of Conduct](https://github.com/pb3lab/ibm3202/blob/master/contributions.md) before making any changes.

## References
1. Chaudhury S, Lyskov S, Gray JJ. PyRosetta: a script-based interface for implementing molecular modeling algorithms using Rosetta. Bioinformatics. 2010;26:689–91. doi:10.1093/bioinformatics/btq007.
2. Abraham MJ, Murtola T, Schulz R, Páll S, Smith JC, Hess B, et al. GROMACS: High performance molecular simulations through multi-level parallelism from laptops to supercomputers. SoftwareX. 2015;1–2:19–25. doi:10.1016/j.softx.2015.06.001.
3. Noel JK, Levi M, Raghunathan M, Lammert H, Hayes RL, Onuchic JN, et al. SMOG 2: A Versatile Software Package for Generating Structure-Based Models. PLOS Comput Biol. 2016;12:e1004794. doi:10.1371/journal.pcbi.1004794.
4. Cock PJA, Antao T, Chang JT, Chapman BA, Cox CJ, Dalke A, et al. Biopython: freely available Python tools for computational molecular biology and bioinformatics. Bioinformatics. 2009;25:1422–3. doi:10.1093/bioinformatics/btp163.
5. Rego N, Koes D. 3Dmol.js: molecular visualization with WebGL. Bioinformatics. 2015;31:1322–4. doi:10.1093/bioinformatics/btu829.
6. Rose AS, Hildebrand PW. NGL Viewer: a web application for molecular visualization. Nucleic Acids Res. 2015;43:W576–9. doi:10.1093/nar/gkv402.
7. Grüning B, Dale R, Sjödin A, Chapman BA, Rowe J, Tomkins-Tinch CH, et al. Bioconda: sustainable and comprehensive software distribution for the life sciences. Nat Methods. 2018;15:475–6. doi:10.1038/s41592-018-0046-7.
8. Katoh K, Standley DM. MAFFT Multiple Sequence Alignment Software Version 7: Improvements in Performance and Usability. Mol Biol Evol. 2013;30:772–80. doi:10.1093/molbev/mst010.
9. Darriba Di, Posada D, Kozlov AM, Stamatakis A, Morel B, Flouri T. ModelTest-NG: A New and Scalable Tool for the Selection of DNA and Protein Evolutionary Models. Mol Biol Evol. 2020;37:291–4. doi:10.1093/molbev/msz189.
10. Kozlov AM, Darriba D, Flouri T, Morel B, Stamatakis A. RAxML-NG: a fast, scalable and user-friendly tool for maximum likelihood phylogenetic inference. Bioinformatics. 2019;35:4453–5. doi:10.1093/bioinformatics/btz305.
11. Webb B, Sali A. Comparative Protein Structure Modeling Using MODELLER. Curr Protoc Bioinforma. 2014;47:5.6.1-5.6.32. doi:10.1002/0471250953.bi0506s47.
12. O’Boyle NM, Banck M, James CA, Morley C, Vandermeersch T, Hutchison GR. Open Babel: An open chemical toolbox. J Cheminform. 2011;3:33. doi:10.1186/1758-2946-3-33.
13. Dolinsky TJ, Czodrowski P, Li H, Nielsen JE, Jensen JH, Klebe G, et al. PDB2PQR: expanding and upgrading automated preparation of biomolecular structures for molecular simulations. Nucleic Acids Res. 2007;35 Web Server:W522–5. doi:10.1093/nar/gkm276.
14. Morris GM, Huey R, Lindstrom W, Sanner MF, Belew RK, Goodsell DS, et al. AutoDock4 and AutoDockTools4: Automated docking with selective receptor flexibility. J Comput Chem. 2009;30:2785–91. doi:10.1002/jcc.21256.
15. Trott O, Olson AJ. AutoDock Vina: Improving the speed and accuracy of docking with a new scoring function, efficient optimization, and multithreading. J Comput Chem. 2010;31:455–61. doi:10.1002/jcc.21334.
16. Michaud-Agrawal N, Denning EJ, Woolf TB, Beckstein O. MDAnalysis: A toolkit for the analysis of molecular dynamics simulations. J Comput Chem. 2011;32:2319–27. doi:10.1002/jcc.21787.
17. Nawrocki EP, Kolbe DL, Eddy SR. Infernal 1.0: inference of RNA alignments. Bioinformatics. 2009;25:1335–7. doi:10.1093/bioinformatics/btp157.
18. Zerihun MB, Pucci F, Peter EK, Schug A. pydca v1.0: a comprehensive software for direct coupling analysis of RNA and protein sequences. Bioinformatics. 2020;36:2264–5. doi:10.1093/bioinformatics/btz892.
19. Mirdita M, Schütze K, Moriwaki Y, Heo L, Ovchinnikov S, Steinegger M. ColabFold: making protein folding accessible to all. Nature Methods. 2022 May 30:1-4. doi:10.1038/s41592-022-01488-1.
