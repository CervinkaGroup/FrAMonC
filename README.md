# FrAMonC Methanol Dimers Library
Platform for Fragment-based Ab Initio Monte Carlo simulations for amorphous molecular materials

Library of Pair interactions of molecules extracted from ab initio Monte Carlo simulations of bulk liquid methanol
in the temperature range 260-300 K and at 100 kPa. Data cover the first solvation shell within bulk liquid so that molecular
dimers with the closest atom-atom contact distance lower than 4 A are included. In total, 970 000 distinct dimers are included 
in Parts A-G of these archives as of July 11, 2025.

Each *.txt file contains information about:
Line 1   - closest atomic contact within the dimer, pair interaction energy calculated at the DLPNO-CCSD(T)/CBS and DFTB3-D4/3ob levels of theory
Line 2   - number of atoms in the dimer
Line 3+  - Cartesian coordinates of the dimers

This dimer library was created by Dr. Ctirad Cervinka at the University of Chemistry and Technology, Prague in year 2025. All inquiries should be
addressed to e-mail address ctirad.cervinka@vscht.cz.

Whenever this dimer library is used, please do cite the associated research article:

C. Cervinka, Introducing the coupled-clusters theory to the amorphous world of liquids and their thermodynamic simulations, J. Am. Chem. Soc., Under Consideration, 2025.
