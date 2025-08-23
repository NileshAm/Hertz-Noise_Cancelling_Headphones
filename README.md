# Hertz-Noise_Cancelling_Headphones
This repository contains all the design files that was needed to make an analog **active noise cancelling headphone**.
## Folder structure
```
.
├── Enclosure design/
│   ├── Assemblies/
│   |    └── *.sldasm
│   ├── Drawings/
│   |    ├── *.slddrw
|   |    └── *.pdf
│   ├── Manufacturing designs/
│   |    └── *.stl
|   └── Parts/
│       └── *.sldprt
├── Circuit design
├── simulation
├── .gitignore
└── README.md
```
## Branching
- **main branch**: contains all the final designs of the headphone
- **circuit branch**: Changes done to the circuit design is done in this branch.
    - **circuit-***: Individual design for the circuit design is done in this branch.<br>
    ex: `circuit-power_amp`
- **enclosure branch**: Changes done to the enclosure design is done in this branch.
    - **enclosure-***: Individual design for the enclosure design is done in this branch.<br>
    ex: `enclosure-headphone_cup`