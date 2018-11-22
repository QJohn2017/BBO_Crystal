# BBO_Crystal
These Matlab codes allow you to calculate the following optical properties of a beta-barium borate (BBO) crystal: 
* the phase-matching angle for the sum-frequency generation (SFG) process (type I)
* the dependence of the reflactive indices on the wavelength.     
   
The reflective indices are calculated using the Sellmeier's equation. Some parameters that are needed for the calculation are taken from the literature (G. Tamosauskas, G. Beresnevicius, D. Gadonas, and A. Dubietis, Opt. Mater. Express, 8, 1410 (2018)).
# The calculation of the phase-matching angle
The phase-matching angle can be calculated by running "PMangle.m." You will be requested to specify the wavelengths of the two input beams (Wavelength_1 and Wavelength_2 in the unit of nm). If you choose the same wavelength for both of the input beams, the nonlinear optical process is classified as the second harmonic generation (SHG).  
# The dependence of the reflective indices on the wavelength
The reflective indices for the extraordinary and ordinary rays can be plotted as a function of the wavelength by running the code "plotreflectiveindex.m." 
