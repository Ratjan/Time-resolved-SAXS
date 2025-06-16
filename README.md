# Time-resolved-SAXS
Python scripts for averaging, subtraction and merging of time-resolved SAXS data (e.g. reaction kinetics, SEC-SAXS).
Requires 1D SAXS data for each frame/time point as a .dat file.
Code is written for a setup with two detectors. The higher q is named 'pilatus' and the lower q 'eiger'. 
Change this if necessary, this may affect the subtraction part, where the scaling of the water peak is based on only the 'pilatus' detector.

Data workflow:
1) TR-SAXS_average.ipynb
2) TR-SAXS_subtraction.ipynb
3) TR-SAXS_merge.ipynb

11/05/2025
Only script for averaging added.

08/06/2025
Added v2 of script for solvent background subtraction. v3 has options to subtract capillary and solvent separately, but not added for time-resolved SAXS data yet.
Added script for merging data v1. This script requires Mantid to be installed in Python.
