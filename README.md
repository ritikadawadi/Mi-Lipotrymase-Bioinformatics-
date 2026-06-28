# Mi-lipotrymase — Bioinformatics Sequence Analysis

**BIIN 430** ·

Computational characterization of a novel mitochondrial-associated lipase-protease (*Canis lupus*), purified from HeLa cells and analyzed from its near-complete amino acid sequence.

## Overview

This project uses sequence-based bioinformatics to predict the structure and function of an uncharacterized protein. Tools spanning homology search, domain prediction, secondary structure, hydrophobicity, transmembrane topology, subcellular localization, and 3D modeling were applied to build a composite functional profile.

**Key findings:** Four major domains (Smac/DIABLO, Lipase, PLAT, Trypsin SPC); no transmembrane domain; localization to extracellular space and mitochondria; likely roles in apoptosis, lipid metabolism, and protein degradation.

## Repository Structure

| Folder | Contents |
|--------|----------|
| `Final_Report/` | Full written report (PDF) |
| `Functional - Structural Domains and Motifs/` | BLAST, InterPro, SMART, CDD, HMMER outputs |
| `Sequence Motifs/` | Motif and binding-site predictions |
| `Secondary Structures/` | PSIPRED, JPred, SCRATCH, PREDATOR results |
| `Hydrophilic - Hydrophobic Regions/` | ProtScale, EMBOSS, SCRATCH plots |
| `Transmembrane Domain/` | TOPCONS, DeepTMHMM, TMAP predictions |
| `Subcellular Localization/` | TargetP, DeepLoc, WoLF PSORT, BUSCA, and related tools |
| `Function Predictions/` | InterPro, DeepGO, ProtIdent outputs |
| `3D Structures/` | AlphaFold/I-TASSER models and domain PDB files |

## Report

See [`Final_Report.pdf`](Final_Report.pdf) for methods, composite diagrams, discussion, and references.
