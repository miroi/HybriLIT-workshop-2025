=================
SOPC phospholipid 
=================

Compute and visualise vibrational frequencies of the SOPC phopholipid.

MOPAC semiemprirical program is utilized for geometry optimization and 
frequency calculations.

Before that, quick preoptimization and MOPAC input preparation of SOPC is achieved via Avogadro2 force-field method.

Afterwards, frequencies are displayed from the aux file with the Avogadro2 program.

In the vibr_frequencies_mopac/ directory we have the prepared input files. 
The entering geometry "sopc_geom_pm7.arc" is from the previous MOPAC run.

The frequencies calculation job takes around 10 minutes on 12 OpenMP threads.

resources
~~~~~~~~~
papers: https://disk.jinr.ru/index.php/s/MzEBqZGXytBNk8n

SOPC: https://pubchem.ncbi.nlm.nih.gov/compound/1-Stearoyl-2-oleoyl-sn-glycero-3-phosphocholine
also in https://molview.org/?cid=24778825

also https://lipidbook.org/lipid/show/id/28.html
     https://www.lipidmaps.org/databases/lmsd/LMGP01010761

todo: fix minor problem of different molecular formula
C44H86NO8P(pubchem) or C44H85NO8P (molview)

