\# FACS Adapters for Petri Dishes



A collection of adapter plates that hold standard round Petri dishes in the ANSI/SLAS microplate footprint, enabling single-cell sorting directly onto agar plates using by FACS. Without an adapter, round Petri dishes cannot be placed on the FACS stage in a reproducible position.



All adapters were designed by Konstantin Neuhaus as part of a PhD project at the Philipps-Universität Marburg and the Biozentrum, University of Basel. The 1 mL custom Petri dish adapter was used in the associated thesis. The 35 mm, 60 mm, and 90 mm adapters were designed for general use in the FACS facility and are included here for completeness.



\---


\## Variants Overview



| Subfolder | Dish size | Capacity | Dish catalogue number (Sarstedt) | Used in thesis |

|-----------|-----------|----------|----------------------------------|----------------|

| `adapter\_1mL\_petri/` | 16 mm diameter custom dish | 6 dishes | — (custom dish, see `petri\_dish\_1mL/`) | ✓ |

| `adapter\_35mm/` | 35 mm | 6 dishes | 82.1135.500 | — |

| `adapter\_60mm/` | 60 mm | 2 dishes | 82.1194.500 | — |

| `adapter\_90mm/` | 90 mm | 1 dish | 82.1472.001 | — |

| `alignment\_plate/` | — | — | — | ✓ |



> \*\*Note:\*\* The 35 mm, 60 mm, and 90 mm adapters were designed for Sarstedt standard Petri dishes. They may fit dishes from other vendors but slight dimensional differences between manufacturers mean fit is not guaranteed.



\---



\## General Design



The outer dimensions of all adapters follow the ANSI/SLAS 1-2004 standard single-well plate footprint (127.76 × 85.48 mm) (See: https://www.slas.org/education/ansi-slas-microplate-standards/). This ensures compatibility with any FACS instrument stage that accepts standard microplate format holders.



All parts were designed in Autodesk Inventor 2026.



\---



\## Fabrication



\### Printer

Bambu Lab X1-Carbon FDM printer



\### Material

\*\*PLA filament\*\* (Bambu Lab PLA Basic)



\### Print Settings

| Parameter | Value |

|-----------|-------|

| Layer height | 0.2mm |

| Infill | 15% |

| Print orientation | Flat (base down) for best dimensional accuracy |



\---



\## Alignment Plate



The `alignment\_plate/` subfolder contains a laser-cut acrylic calibration plate. This plate mounts onto any of the adapters in place of the Petri dishes and features engraved concentric rings at each dish position, making sort drop landing positions visible during stage calibration.



\*\*Calibration procedure:\*\*

1\. Mount the alignment plate onto the adapter

2\. Place the adapter on the FACS stage

3\. Sort a small number of events and observe where the drops land relative to the engraved rings

4\. Adjust the sort position until drops land at the centre ring of each position

5\. Remove the alignment plate, insert Petri dishes, and begin sorting



Calibration should be performed at the start of each sort session as the stage position can shift between sessions.



See `alignment\_plate/README.md` for fabrication details.



\---





\## File Structure



```

facs\_adapters/

├── README.md                        

│

├── adapter\_1mL\_petri/

│   ├── facs\_adapter\_1mL.ipt

│   ├── facs\_adapter\_1mL.step

│   ├── facs\_adapter\_1mL.stl

│   └── technical\_drawing.pdf

│

├── adapter\_35mm/

│   ├── facs\_adapter\_35mm.ipt

│   ├── facs\_adapter\_35mm.step

│   └── facs\_adapter\_35mm.stl

│

├── adapter\_60mm/

│   ├── facs\_adapter\_60mm.ipt

│   ├── facs\_adapter\_60mm.step

│   └── facs\_adapter\_60mm.stl

│

├── adapter\_90mm/

│   ├── facs\_adapter\_90mm.ipt

│   ├── facs\_adapter\_90mm.step

│   └── facs\_adapter\_90mm.stl

│

└── alignment\_plate/

&#x20;   ├── alignment\_plate.dxf

&#x20;   ├── alignment\_plate.step

&#x20;   └── technical\_drawing.pdf

```



\---



\## Citation



If you use these designs, please cite:



```

Neuhaus, K. (2026). Novel microscopy-based approaches to study bacterial communities.

PhD thesis, Philipps-Universität Marburg.

```

