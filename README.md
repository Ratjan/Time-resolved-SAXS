# Time-resolved-SAXS
Python scripts for averaging, subtraction and merging of time-resolved SAXS data (e.g. reaction kinetics, SEC-SAXS).
Requires 1D SAXS data for each frame/time point as a .dat file.
Code is written for a setup with two detectors simultaneously. The higher q is named 'pilatus' and the lower q 'eiger'. 
Change this if necessary, this may have effects in the subtraction part, where the scaling of the water peak is based on only the 'pilatus' detector.

11/05/2025
Only script for averaging added.
