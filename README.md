# The Unique Structure Prototypes of All Materials

This repository contains the datasets and code associated with the Master's thesis **"The Unique Structure Prototypes of All Materials"** (Tel Aviv University, 2025).

## 📖 Overview

Crystal structure offers a compact, composition-independent basis for understanding materials behavior and accelerating discovery. This project presents an automated and reproducible workflow for identifying structure prototypes directly from atomic geometries, rather than relying on database metadata.

By analyzing **23,160** experimentally observed thermodynamic ground state inorganic materials from the Materials Project, we utilized a geometric matching algorithm to identify unique structural frameworks.

## 📊 Data Availability

The full lists of prototypes is freely available on GitHub. Each prototype is shown with the following information: 
* **Filename** (as obtained from the Materials Project)
* **Chemical formula**
* **Match count** (how many materials matched this prototype)
* **Space group** (both in Hermann-Mauguin and IUCr notation)
* **Orientation matrix** (in Ångström)
* **Fractional coordinates** for each atom

### Example Entry
```text
Filename: mp-2605.cif CaO appeared: 122 times
Space Group: Fm-3m no. 225
Orientation Matrix:
2.94 0.00 1.70
0.98 2.78 1.70
0.00 0.00 3.40
Atoms Locations:
Ca [0. 0. 0.]
O [0.5 0.5 0.5]
