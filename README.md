# Legalized-Placement-for-Discrete-Spacing-Costs

The benchmark folder contains all the testcases used for physical design evaluation.  
Each testcase is organized in its own subfolder, which includes the following four files:

- **cells_modified.lef**  
  This is a modified LEF (Library Exchange Format) file containing the physical information of standard cells, such as cell dimensions, pin locations, and metal layer details.

- **diffusion.txt**  
  This text file contains information related to diffusion height information for each cell type in the design.  
  For example, the entry `in01f01X2HE (4,2) (3,4)` indicates that the cell type `in01f01X2HE` is a double-row-height cell, with diffusion heights of 4 and 2 for the left and right lower rows, respectively, and 3 and 4 for the left and right higher rows, respectively.

- **placed.def**  
  The DEF (Design Exchange Format) file records the placement results of all cells and their interconnections in the design.

- **tech.lef**  
  The technology LEF file describes the process technology rules, including the number of metal layers, layer thickness, and design rules.
