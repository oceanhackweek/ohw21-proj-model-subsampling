## ohw21-proj-model-subsampling
## OceanHackWeek21 project to subsample high-resolution model output as if by gliders, ships, or other in situ platforms

The goal of this project is to create a Python package that takes an input trajectory (e.g., the path of an ocean glider), subsamples output from a high-resolution ocean simulation along that trajectory, and returns a set of subsampled variables (e.g., standard physical variables temperature, salinity, velocity; derived physical quantities such as steric height; biogeochemical quantities if available).  This package is potentially useful for designing in situ sampling strategies, interpreting in situ data, etc. 

Tasks:
1. Load model data from a specific region (e.g., ROMS output in the California Current from CenOOS; MITgcm regional llc4320 data)
2. Create trajectory file (could be made up or a real glider/ship trajectory)
3. Interpolate model data to the trajectory
4. Compare simulated (interpolated) data to full model output


