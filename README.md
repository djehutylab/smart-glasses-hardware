<p align="center">
  <a href="https://github.com/djehutylab/smart-glasses-hardware">📦 <b>Repo:</b> smart-glasses-hardware</a> &nbsp;|&nbsp; 
  <a href="https://github.com/djehutylab/smart-glasses-hardware">🟢 <b>Status:</b> Active R&D</a> &nbsp;|&nbsp; 
  <a href="#license">📜 <b>License:</b> CERN-OHL-P v2</a>
</p>
<hr>
 

## 🔬 About This Repository
This repository hosts the physical engineering files for the Djehuty Lab smart glasses project. Keeping these files isolated allows mechanical, optical, and electrical engineers to find, audit, and manufacture our physical designs quickly and efficiently.

## 📂 Repository Structure
```text
smart-glasses-hardware/
├── .github/
│   └── ISSUE_TEMPLATE/        # For bug reports (e.g., PCB design errors)
├── hardware/
│   ├── electronics/           # EDA / PCB Files
│   │   ├── kicad-project/     # Schematic and layout files (KiCad/Altium)
│   │   └── manufacturing/     # Production files
│   │       ├── gerbers/       # Gerber files for PCB manufacturing
│   │       └── bom.csv        # Bill of Materials (components, part numbers)
│   └── mechanics/             # Physical chassis & optics
│       ├── cad-models/        # STEP, IGES, or Fusion360 source files
│       └── 3d-print/          # STL/3MF files for rapid prototyping
├── LICENSE                    # CERN-OHL-P license text
└── README.md                  # Hardware overview and 3D printing specs
```

## 📜 License
This hardware repository is licensed under the **CERN Open Hardware Licence Version 2 - Permissive (CERN-OHL-P v2)**. See the `LICENSE` file for full terms.
