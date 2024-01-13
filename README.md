# Monte-Carlo-Ising-model

Simple Python codes for implementing the Monte Carlo algorithm to evaluate the ensemble average of the energy (E), spin magnetization (Sz), two-spin correlation, specific heat capacity (C), and susceptibility (x) in the following Ising models:

**(1) Ising1D.ipynb** <br>
  For the 1D model, there should be no phase transition. The apparent peak in C and x there is due to finite-size effect.
 
**(2) Ising2D-square.ipynb** <br>
  For the 2D model, the critical value for the spin-spin interaction can be deduced.

**(3) bilayer-Ising_with-4-spin-interaction.ipynb** <br>
  For the bilayer 2D system with 4 spin interaction, the critical behaviour is very rich. <br>
  Ref: F. W. Wu, Phys. Rev. B **4**, 2312 (1971). <br>
  One can study this critical behaviour by tuning the parameters alpha and beta in the code

For each program, the following libraries are imported: <br>
_numpy_: for basic numerical calculation   
_matplotlib_: for plotting the numerical results
