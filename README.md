# Identification of Lead Molecules for Proteins Associated with Migraine

Undergraduate research project, Sri Ramachandra Institute of Higher Education
and Research, Chennai (Jan–Jun 2025). Mentored by Dr. C.R. Hemalatha,
Head of Bioinformatics.

This project reproduces the in silico workflow of a published study:
[Original paper: authors, year, title, journal]

## Overview
Familial hemiplegic migraine is linked to mutations in three genes: **CACNA1A**,
**SCN1A**, and **ATP1A2**. This project studied the proteins these genes encode
and screened chemical and phytochemical compounds as potential lead molecules,
using a computational drug discovery pipeline.

## Workflow
1. **Protein structures:** retrieved 3D structures of CACNA1A, SCN1A, and ATP1A2
   from the RCSB Protein Data Bank
2. **Interaction network:** mapped protein-protein interactions with STRING and
   pathways with KEGG, including the glutamatergic synapse
3. **Compound selection:** selected candidate chemicals and phytochemicals from
   PubChem for each target and screened them with Lipinski's Rule of Five
4. **Molecular docking:** docked compounds against each target in PyRx and
   visualized binding poses in UCSF Chimera
5. **ADME profiling:** predicted pharmacokinetic properties with SwissADME,
   including BOILED-Egg plots for absorption and brain penetration
6. **Toxicity profiling:** predicted toxicity with ProTox 3.0

## Tools and databases
RCSB PDB · STRING · KEGG · DAVID · OMIM · ENCODE · PubChem · PyRx ·
UCSF Chimera · SwissADME · ProTox 3.0

## Results
*Docking scores, ADME and toxicity tables, and figures will be added soon.*

## Team
[Your name and teammates' names]
Mentor: Dr. C.R. Hemalatha, SRIHER
