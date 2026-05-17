 ECAL Radiation Damage and Calibration Model

This project studies radiation damage effects in the LHCb Electromagnetic Calorimeter (ECAL) using simulated calorimeter cluster data. The code builds a toy model based on longitudinal shower development and radiation dose dependent efficiency loss.


 Main Features
* Loads and processes ROOT cluster data using `uproot`
* Separates photons, electrons, and hadrons
* Builds 3D radiation dose distributions in ECAL depth (z)
* Models electromagnetic shower profiles using gamma-distribution parameterization
* Uses external Geant4 hadron shower profiles from CSV input
* Computes integrated radiation dose versus detector depth
* Applies a dose-based detector efficiency degradation model
* Produces detector response curves and inverse-response calibration factors


The code generates several physics and detector-performance plots, including:
* Particle energy distributions
* EM and hadron longitudinal shower profiles
* Radiation dose vs detector depth
* x-y projected dose maps
* Efficiency degradation models
* Detector response functions
* Calibration factor curves

 Packegas used:
* Python
* NumPy
* Matplotlib
* Pandas
* SciPy
* Uproot
