# NOVUS LA TRIADA
## Repositorio abierto de laboratorios prácticos computacionales en la nube para educación STEM

Este repositorio cuenta con distintos cuadernos de Jupyter con instrucciones y código de Bash y Python para la ejecución de laboratorios prácticos en distintas disciplinas utilizando [Google Colaboratory](https://colab.research.google.com/?hl=es), un servicio alojado en la nube que no requiere configuración y que ofrece acceso gratuito a recursos de computación, incluyendo CPUs, GPUs y TPUs.

Cada cuaderno de Jupyter consiste de un laboratorio práctico con instrucciones de las actividades a realizar, la instalación de *software* adicional a utilizar para cada laboratorio, y distintas celdas de texto y de código en Bash y Python para ejecutar tareas de cómputo, análisis y visualización de datos. Además, todos los laboratorios prácticos se encuentran disponibles tanto en español como en inglés.

## 1. Laboratorios de Modelado y Simulación Molecular

| Tutorial | Descripción | Versión en español |  Versión en inglés | *Software* Adicional |
|----------|-------------|--------------------|--------------------|----------------------|
| Lab.01   | Uso de Colab y Revisión de Bases de Datos de Biomoléculas | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutoriales/ModSimMol/lab01_intro.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutorials/ModSimMol/lab01_intro.ipynb) |  |
| Lab.02   | Visualizando y Comparando Estructuras Moleculares en Google Colab usando py3Dmol | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutoriales/ModSimMol/lab02_molviz.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutorials/ModSimMol/lab02_molviz.ipynb) | Biopython [1], py3Dmol [2], NGL Viewer [3] |
| Lab.03   | Análisis Filogenético usando biopython y RAxML | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutoriales/ModSimMol/lab03_phylo.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutorials/ModSimMol/lab03_phylo.ipynb) | Biopython [1], miniconda [4], MAFFT [5], ModelTest-ng [6], RAxML-ng [7] |
| Lab.04   | Modelado Comparativo usando MODELLER | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutoriales/ModSimMol/lab04_cm.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutorials/ModSimMol/lab04_cm.ipynb) | Biopython [1], py3Dmol [2], MODELLER [8] |
| Lab.05   | Modelado de Proteínas de Membrana usando PyRosetta | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutoriales/ModSimMol/lab05_MP_rosetta.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutorials/ModSimMol/lab05_MP_rosetta.ipynb) | py3Dmol [2], pyRosetta [9] |
| Lab.06   | Acoplamiento Molecular usando Autodock Vina | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutoriales/ModSimMol/lab06_docking.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutorials/ModSimMol/lab06_docking.ipynb) | Biopython [1], py3Dmol [2], miniconda [4], Open Babel [10], pdb2pqr [11], MGLTools [12], Autodock Vina [13] |
| Lab.07   | Dinámica Molecular usando GROMACS | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutoriales/ModSimMol/lab07_MDsims.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutorials/ModSimMol/lab07_MDsims.ipynb) | Biopython [4], py3Dmol [5], NGL Viewer [6], GROMACS [14] |
| Lab.08   | Análisis de trajectorias de MD usando MDAnalysis | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutoriales/ModSimMol/lab08_MDanalysis.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutorials/ModSimMol/lab08_MDanalysis.ipynb) | py3Dmol [5], MDAnalysis [15] |
| Lab.09   | Simulaciones de plegado de proteínas usando modelos basados en estructuras (SBM) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutoriales/ModSimMol/lab09_SMOGfolding_docker.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutorials/ModSimMol/lab09_SMOGfolding_docker.ipynb) | Biopython [1], py3Dmol [2], NGL Viewer [3], udocker [16], SMOG2 Docker [17], SBM-enhanced GROMACS [17] |
| Lab.10   | Cambios conformacionales usando modelos basados en estructuras (SBM) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutoriales/ModSimMol/lab10_SMOGdual_docker.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutorials/ModSimMol/lab10_SMOGdual_docker.ipynb) | Biopython [1], py3Dmol [2], NGL Viewer [3], udocker [16], SMOG2 Docker [17], SBM-enhanced GROMACS [17] |
| Lab.11   | Predicción de interacciones en ARN mediante análisis coevolutivos de secuencias | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutoriales/ModSimMol/lab11_rnaDCA.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutorials/ModSimMol/lab11_rnaDCA.ipynb) | Biopython [1], py3Dmol [2], infernal [18], pyDCA [19] |
| Lab.12   | Plegado de proteínas ab initio usando Rosetta | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutoriales/ModSimMol/lab12_abinitioRosetta.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutorials/ModSimMol/lab12_abinitioRosetta.ipynb) | Biopython [1], py3Dmol [2], pyRosetta [9] |
| Lab.13   | Combinando DCA y SBM para predecir estructuras de proteínas | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutoriales/ModSimMol/lab13_protDCASBM.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutorials/ModSimMol/lab13_protDCASBM.ipynb) | Biopython [1], py3Dmol [2], SMOG2 [17], SBM-enhanced GROMACS [17], pyDCA [19] |

**Autoras y Autores:** Felipe Engelberger<sup>1,2,3</sup>, Pablo Galaz-Davison<sup>1,2</sup>, Graciela Bravo<sup>4</sup>, Maira Rivera<sup>1,2,5</sup>, Jorge González-Higueras<sup>1,2</sup>, Camila Neira-Mazuhier<sup>1,2</sup> y César A. Ramírez Sarmiento<sup>1,2</sup>.

<sup>1</sup>Instituto de Ingeniería Biológica y Médica, Pontificia Universidad Católica de Chile, Santiago, Chile.

<sup>2</sup>ANID – Instituto Milenio de Biología Integrativa (iBio), Santiago, Chile.

<sup>3</sup>Institute for Drug Discovery, Leipzig University, Leipzig, Alemania.

<sup>4</sup>Departamento de Ingeniería Química y Bioprocesos, Escuela de Ingeniería, Pontificia Universidad Católica de Chile, Santiago, Chile.

<sup>5</sup>Department of Chemistry, Faculty of Science, McGill University, Montreal, Canada.

**Repositorio Original:** https://github.com/pb3lab/ibm3202

##
## 2. Laboratorios de Biodiversidad de Moléculas en Colombia

| Tutorial | Descripción | Versión en español |  Versión en inglés | *Software* Adicional |
|----------|-------------|--------------------|--------------------|----------------------|
| Lab.00   | Uso de Colab | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutoriales/Biomolecules/Tutorial00_biomolecules.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutorials/Biomolecules/Tutorial00_biomolecules.ipynb) |  |
| Lab.01   | Explorando la riqueza de la biodiversidad colombiana: Una mirada de cerca a la biomolécula galantamina | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutoriales/Biomolecules/Tutorial01_biomolecules.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutorials/Biomolecules/Tutorial01_biomolecules.ipynb) | Biopython [1], py3Dmol [2] |
| Lab.02   | Explorando la riqueza de la biodiversidad colombiana: Una mirada de cerca a la biomolécula kaempferol | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutoriales/Biomolecules/Tutorial02_biomolecules.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutorials/Biomolecules/Tutorial02_biomolecules.ipynb) | Biopython [1], py3Dmol [2] |
| Lab.03   | Explorando la riqueza de la biodiversidad colombiana: Una mirada de cerca a la biomolécula quercetina | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutoriales/Biomolecules/Tutorial03_biomolecules.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutorials/Biomolecules/Tutorial03_biomolecules.ipynb) | Biopython [1], py3Dmol [2] |
| Lab.04   | Explorando la riqueza de la biodiversidad colombiana: Una mirada de cerca a la biomolécula resveratrol | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutoriales/Biomolecules/Tutorial04_biomolecules.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutorials/Biomolecules/Tutorial04_biomolecules.ipynb) | Biopython [1], py3Dmol [2] |
| Lab.05   | Explorando la riqueza de la biodiversidad colombiana: Una mirada de cerca a la biomolécula luteolina | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutoriales/Biomolecules/Tutorial05_biomolecules.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutorials/Biomolecules/Tutorial05_biomolecules.ipynb) | Biopython [1], py3Dmol [2] |
| Lab.06   | Explorando la riqueza de la biodiversidad colombiana: Una mirada de cerca a la biomolécula apigenina | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutoriales/Biomolecules/Tutorial06_biomolecules.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutorials/Biomolecules/Tutorial06_biomolecules.ipynb) | Biopython [1], py3Dmol [2] |
| Lab.07   | Explorando la riqueza de la biodiversidad colombiana: Una mirada de cerca a la biomolécula epicatequina | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutoriales/Biomolecules/Tutorial07_biomolecules.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutorials/Biomolecules/Tutorial07_biomolecules.ipynb) | Biopython [1], py3Dmol [2] |
| Lab.08   | Explorando la riqueza de la biodiversidad colombiana: Una mirada de cerca a la biomolécula cannabidiol | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutoriales/Biomolecules/Tutorial08_biomolecules.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/NOVUS/blob/master/tutorials/Biomolecules/Tutorial08_biomolecules.ipynb) | Biopython [1], py3Dmol [2] |

**Autoras y Autores:** Juan Fernando Meza Prada<sup>1</sup>, Cielo Leon Ramos<sup>1</sup>, Francisco Bohorquez Martínez<sup>1</sup>, Wilson Rodríguez Escucha<sup>1</sup>, Adriana Bernal Giraldo<sup>1</sup>, María de los Ángeles Domínguez Cuenca<sup>2</sup>, César A. Ramírez Sarmiento<sup>3,4</sup>, María Francisca Villegas<sup>1</sup> y Andrés Gonzalez Barrios<sup>1,5</sup>.

<sup>1</sup>Departamento de Ciencias Biológicas, Universidad de los Andes, Bogotá, Colombia.

<sup>2</sup>Instituto para el Futuro de la Educación, Tecnolólogico de Monterrey, Monterrey, México

<sup>3</sup>Instituto de Ingeniería Biológica y Médica, Pontificia Universidad Católica de Chile, Santiago, Chile.

<sup>4</sup>ANID – Instituto Milenio de Biología Integrativa (iBio), Santiago, Chile.

<sup>5</sup>Grupo de Diseño de Productos y Procesos, Departaento de Ingeniería Química y de Alimentos, Universidad de los Andes, Bogotá, Colombia.

**Repositorio original:** https://github.com/juferprada97/Biomolecules-tutorials

## ¡Cita nuestro trabajo!

Si utilizas estos tutoriales para tus investigaciones y/o docencia, por favor **cita nuestro trabajo publicado**

Engelberger F, Galaz-Davison P, Bravo G, Rivera M, Ramírez-Sarmiento CA (2021) Developing and Implementing Cloud-Based Tutorials that Combine Bioinformatics Software, Interactive Coding and Visualization Exercises for Distance Learning on Structural Bioinformatics. _J Chem Educ 98_(5): 1801-1807. **doi:** [10.1021/acs.jchemed.1c00022](https://dx.doi.org/10.1021/acs.jchemed.1c00022)

## Contribuciones y Código de Conducta

Por favor lee nuestras reglas para [Contribuciones y Código de Conducta](https://github.com/pb3lab/ibm3202/blob/master/contributions.md) antes de hacer cambios.

## Referencias
1. Cock PJA, Antao T, Chang JT, Chapman BA, Cox CJ, Dalke A, et al. Biopython: freely available Python tools for computational molecular biology and bioinformatics. Bioinformatics. 2009;25:1422–3. doi:10.1093/bioinformatics/btp163.
2. Rego N, Koes D. 3Dmol.js: molecular visualization with WebGL. Bioinformatics. 2015;31:1322–4. doi:10.1093/bioinformatics/btu829.
3. Rose AS, Hildebrand PW. NGL Viewer: a web application for molecular visualization. Nucleic Acids Res. 2015;43:W576–9. doi:10.1093/nar/gkv402.
4. Grüning B, Dale R, Sjödin A, Chapman BA, Rowe J, Tomkins-Tinch CH, et al. Bioconda: sustainable and comprehensive software distribution for the life sciences. Nat Methods. 2018;15:475–6. doi:10.1038/s41592-018-0046-7.
5. Katoh K, Standley DM. MAFFT Multiple Sequence Alignment Software Version 7: Improvements in Performance and Usability. Mol Biol Evol. 2013;30:772–80. doi:10.1093/molbev/mst010.
6. Darriba Di, Posada D, Kozlov AM, Stamatakis A, Morel B, Flouri T. ModelTest-NG: A New and Scalable Tool for the Selection of DNA and Protein Evolutionary Models. Mol Biol Evol. 2020;37:291–4. doi:10.1093/molbev/msz189.
7. Kozlov AM, Darriba D, Flouri T, Morel B, Stamatakis A. RAxML-NG: a fast, scalable and user-friendly tool for maximum likelihood phylogenetic inference. Bioinformatics. 2019;35:4453–5. doi:10.1093/bioinformatics/btz305.
8. Webb B, Sali A. Comparative Protein Structure Modeling Using MODELLER. Curr Protoc Bioinforma. 2014;47:5.6.1-5.6.32. doi:10.1002/0471250953.bi0506s47.
9. Chaudhury S, Lyskov S, Gray JJ. PyRosetta: a script-based interface for implementing molecular modeling algorithms using Rosetta. Bioinformatics. 2010;26:689–91. doi:10.1093/bioinformatics/btq007.
10. O’Boyle NM, Banck M, James CA, Morley C, Vandermeersch T, Hutchison GR. Open Babel: An open chemical toolbox. J Cheminform. 2011;3:33. doi:10.1186/1758-2946-3-33.
11. Dolinsky TJ, Czodrowski P, Li H, Nielsen JE, Jensen JH, Klebe G, et al. PDB2PQR: expanding and upgrading automated preparation of biomolecular structures for molecular simulations. Nucleic Acids Res. 2007;35 Web Server:W522–5. doi:10.1093/nar/gkm276.
12. Morris GM, Huey R, Lindstrom W, Sanner MF, Belew RK, Goodsell DS, et al. AutoDock4 and AutoDockTools4: Automated docking with selective receptor flexibility. J Comput Chem. 2009;30:2785–91. doi:10.1002/jcc.21256.
13. Trott O, Olson AJ. AutoDock Vina: Improving the speed and accuracy of docking with a new scoring function, efficient optimization, and multithreading. J Comput Chem. 2010;31:455–61. doi:10.1002/jcc.21334.
14. Abraham MJ, Murtola T, Schulz R, Páll S, Smith JC, Hess B, et al. GROMACS: High performance molecular simulations through multi-level parallelism from laptops to supercomputers. SoftwareX. 2015;1–2:19–25. doi:10.1016/j.softx.2015.06.001.
15. Michaud-Agrawal N, Denning EJ, Woolf TB, Beckstein O. MDAnalysis: A toolkit for the analysis of molecular dynamics simulations. J Comput Chem. 2011;32:2319–27. doi:10.1002/jcc.21787.
16. Gomes J, Bagnaschi E, Campos I, David M, Alves L, Martins J, et al. Enabling rootless Linux Containers in multi-user environments: the udocker tool. Comput Phys Commun. 2018;232:84-97. doi:10.1016/j.cpc.2018.05.021
17. Noel JK, Levi M, Raghunathan M, Lammert H, Hayes RL, Onuchic JN, et al. SMOG 2: A Versatile Software Package for Generating Structure-Based Models. PLOS Comput Biol. 2016;12:e1004794. doi:10.1371/journal.pcbi.1004794.
18. Nawrocki EP, Kolbe DL, Eddy SR. Infernal 1.0: inference of RNA alignments. Bioinformatics. 2009;25:1335–7. doi:10.1093/bioinformatics/btp157.
19. Zerihun MB, Pucci F, Peter EK, Schug A. pydca v1.0: a comprehensive software for direct coupling analysis of RNA and protein sequences. Bioinformatics. 2020;36:2264–5. doi:10.1093/bioinformatics/btz892.
