The importance of homogeneously nucleated dislocation packet topology on plastic dissipation under shock conditions
===================

Data Organization
-----------------

- Two main folders are **Ideal** and **NonIdeal**
- **NonIdeal**: includes a folder for the 64 loop system  with the 10 different iterations
- **Ideal**: includes folders named based on the number of loops and one for the SQS approach, each folder includes the 10 different iterations
- The iterations are folders named simply from 1 to 10

Output Files
-----------------

- **dat files**: ddd-results, densities.dat, resolved-stress.dat, stress-strain.dat, and velocities-.dat
- **ddd-results**:  Output file containing the key simulation results: macroscopic average strain/stress values in %/MPa, equivalent stress/strain in %/MPa, plastic strain in %, total dislocation density in m^(-2), junction dislocation density in m^(-2), and average time step value in s
- **densities**: Output file containing the dislocation densities (in m^(-2)) on the different slip systems
- **resolved-stress**: Output file containing the resolved shear stress (in MPa) on the different slip systems 
- **stress-strain**: Output file containing the macroscopic average strain/stress values (in %\/MPa)
- **velocities**: Output file containing the average dislocation velocities (in m\/s) on the different slip systems