# Phonon-scattering-and-transport-in-polycyrstals
Mathematica (MMA) scripts that implement the phonon scattering and transport theory presented in "Phonon diffraction and dimensionality crossover in phonon-interface scattering" by Hanus, Garg, and Snyder (2018). 

## Overview
The scripts follow closely with the presentation in the paper. Simply execute the "Initialize functions" cell in GB-strain-scattering.nb or GB-strain-scattering_modeling.nb which opens and runs GB-strain-scattering_init.nb. Descriptions of all functions called in GB-strain-scattering.nb or GB-strain-scattering_modeling.nb can be found in GB-strain-scattering_init.nb.

Note, all variabls need to be defined globally which may interfere with other scripts you have running.

If you do not have Mathematica you can view the scripts in a readable format using the Free Wolfram Player (http://www.wolfram.com/cdf-player/), or simply opening the PDF file.

### GB-strain-scattering_init.nb
Defines constants, functions, and plot formatting. 

### GB-strain-scattering.nb
Computes the theoretical model for phonon scattering off of the strain field from a symmetric tilt grain boundary presented in Section 4. The full summation (Eq. B.13) is compared to the semi-emperical formula (Eq. 21). 

### GB-strain-scattering_modeling.nb
Performs the thermal transport modeling presented in Section 5. We follow the same procedure as that given by Wang et al. (2011), where Debye and Born-von Karman dispersion relations are applied to the Callaway model for phonon thermal conductivity. 
