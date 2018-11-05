# NEGF-phonon-1D-matlab
A 100-line Matlab code for phonon transport using the NEGF method in 1D atomic chain

## Features

* This is a simple but working code for calculating the phonon transmission in 1D homogeneous atomic chain.
* This code is useful for teaching the NEGF method of phonon transport.
  
## File organizations

* A script for testing:
  * test_ballistic.m: calculates the transmission in 1D homogeneous atomic chain

* The testing script calls
  * the driver function "find_T" to do the calculations

* The driver function "find_T" calls
  * the "find_H" function to construct the harmonic matrix
  * the "find_Sigma" function to calculate the self-energies of the leads
  * the "find_T1" function to calculate the transmission for a single phonon frequency
  
* The "find_Sigma" function calls 
  * the "find_g00" function to calculate the surface Green's function
  
## Unit system

* I use the following basic units:
  * Spring constant between two atoms: k=1
  * Mass of the atom: m=1

## Running the examples

* Run the "test_ballistc.m" script to get the ballistic transmission in in 1D homogeneous atomic chain.

## Contact

* Zheyong Fan: brucenju(at)gmail.com
