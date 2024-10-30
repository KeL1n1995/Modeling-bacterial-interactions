# Modeling Bacterial Interactions

## Overview
This project focuses on modeling bacterial interactions using various computational tools and datasets. It includes code for different modeling approaches and evaluation methods, as well as data files in multiple formats.

![image](https://github.com/user-attachments/assets/815a6f21-c270-400a-8807-b13e30952d0c)

## Prerequisites
- **software:**  `MATLAB 2020a` or a later version
- **Packages:** `git`, `curl`, `COBRA Toolbox 3.0`
- **Solver:** `IBM CPLEX 12.10` or `GUROBI 9.1.1`

## Code Availability
The codes for the following methods can be found in the `Modeling-bacterial-interactions/code` directory:

- **pFBA**: Results and scripts for the parsimonious Flux Balance Analysis (pFBA) of microbial community models.
- **dFBA**: Results and scripts for dynamic Flux Balance Analysis (dFBA) simulations under multi-strain interactions.
- **Memote**: The model is converted from xls format to sbml format for memote analysis.
- **DADA2 R**: R scripts for processing 16S rRNA gene sequences.

## Data Availability
Data files are organized in the following directories:

- **Model Files (MAT Format)**: Located in `Modeling-bacterial-interactions/data/ModelInMatFormat`
- **Model Files (SBML Format)**: Located in `Modeling-bacterial-interactions/data/ModelInSBMLFormat`
- **Memote Evaluation Files**: Quality control report results from the genome-scale metabolic model testing suite (Memote).Located in `Modeling-bacterial-interactions/data/MemoteEvaluationFiles`
- **Figure Data**: Contains raw data and corresponding R code for generating figures (Fig.1 to Fig.4), found in `Modeling-bacterial-interactions/data/FigureData`.

---
<span style="font-weight: bold;">
   Note: For detailed instructions on using these files, please refer to the README files located in each subfolder !
</span> 

---

## Project Directory Structure
The project contains the following files and directories:

```
Modeling Bacterial Interactions：
│  LICENSE
│  README.md
├─ code
│  ├─ README.md
│  ├─ DADA2
│  │      DADA2.R
│  │      README.md
│  ├─ dFBA
│  │      addSecBioRatio.m
│  │      CalculateGrowthR.m
│  │      ClassRxnsMetsList.m
│  │      CsourcesMets.mat
│  │      fastSecRatio.m
│  │      InitConcentrations.m
│  │      InorgMets.mat
│  │      M2SMatrixFBA.m
│  │      M2SMatrixLB.m
│  │      M2SMatrixPFBA.m
│  │      M2SMatrixUB.m
│  │      Main.m
│  │      pFBA01.mat
│  │      pFBA100.mat
│  │      PreSetBound.m
│  │      README.md
│  │      StrainModel.mat
│  ├─ Memote
│  │      memote.py
│  │      readCbModel.m
│  │      README.md
│  │      readtable.m
│  │      table2cell.m
│  │      writeSBML.m
│  │      xls2xml.m
│  └─ pFBA
│          combineTwoModel.m
│          convertToIrreversibleModel.m
│          GetAllCombination.m
│          GetEnhancedCombination.m
│          getEssensialReaction.m
│          getImportantRxn.m
│          GetMedium.m
│          GetMultiSpeciesModel.m
│          LDmain.m
│          Mymedium.txt
│          performLD.m
│          README.md
│          validateModel.m
└─ data
    ├─ README.md
    ├─ FigureData
    │  ├─ Fig.1
    │  │      Fig.1A.xlsx
    │  │      Fig.1B.xlsx
    │  │      Fig.1C.xlsx
    │  │      Fig.1D.xlsx
    │  ├─ Fig.2
    │  │      Fig.2A.xlsx
    │  │      Fig.2B.xlsx
    │  ├─ Fig.3
    │  │      Fig.3.R
    │  │      Fig.3A.xlsx
    │  │      Fig.3B.xls
    │  │      Fig.3C.xlsx
    │  │      Fig.3D.xls
    │  │      Flux.txt
    │  └─ Fig.4
    │          cellgrowth.txt
    │          Fig.4.R
    │          Fig.4A.xlsx
    │          Fig.4B.xlsx
    │          Fig.4C.xlsx
    │          Fig.4D.xlsx
    │          metabolites.txt
    ├─ MemoteEvaluationFiles
    │      A.hydrophila.html
    │      P.gergoviae.html
    │      README.md
    │      S.putrefaciens.html
    │      V.alginolyticus.html
    ├─ ModelInMatFormat
    │      A.hydrophila.mat
    │      P.gergoviae.mat
    │      README.md
    │      S.putrefaciens.mat
    │      V.alginolyticus.mat
    └─ ModelInSBMLFormat
            A.hydrophila.xml
            P.gergoviae.xml
            README.md
            S.putrefaciens.xml
            V.alginolyticus.xml
```

## Contributing
Contributions to improve the code and data organization are welcome. Please refer to the individual README files for guidance on how to contribute to specific components of the project.


 
