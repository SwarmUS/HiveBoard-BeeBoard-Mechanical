# HiveBoard-BeeBoard-Mechanical

This repository contains the 3D models of the HiveBoard, BeeBoard and their mechanical cases. These boards are developed by the  SwarmUS team and their schematics and other design files can be found at [Electical](https://github.com/SwarmUS/Electrical).

## Requirements
- Solidworks 2021

### Repository structure

------

```
HiveBoard-BeeBoard-Mechanical
├── BeeBoardCase
│   ├── case
|   ├── outputs
|   ├── BeeBoard.SLDPRT
|   ├── supported_BeeBoard.SLDASM
│   └── UWB_antenna.SLDPRT
├── HiveBoardCase
│   ├── case
|   ├── HiveBoardComplete
|   ├── outputs
|   ├── HiveBoard.SLDPRT 
│   └── supported_HiveBoard.SLDPRT
└── README.md
```

#### BeeBoardCase

- **case**: Contains all the mechanical parts of the case of the BeeBoard. 
-  **outputs**: Fabrication files (.STL) to 3D print the case.
- **BeeBoard.SLDPRT**: CAD of the board itself. It was fetch from the  exported .STEP of the Altium project found at  [Electical](https://github.com/SwarmUS/Electrical).
- **supported_BeeBoard.SLDASM**: Assembly of the BeeBoard with it's case.
- **UWB_antenna.SLDPRT**: Approximated 3D model of the antennas used on the BeeBoard.

#### HiveBoardCase

- **case**: Contains all the mechanical parts of the case of the HiveBoard. 
- **HiveBoardComplete**: Folder that contains the 3D model of all components on the HiveBoard and the HiveBoard itself.
-  **outputs**: Fabrication files (.STL) to 3D print the case.
- **HiveBoard.SLDPRT**: CAD of the board itself. It was fetch from the  exported .STEP of the Altium project found at  [Electical](https://github.com/SwarmUS/Electrical).
- **supported_HiveBoard.SLDASM**: Assembly of the HiveBoard with it's case.

