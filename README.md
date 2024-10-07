# multiobj-self-assembly
This jupyter notebook finds converged parameters for the GPR kernel for thermodynamic and kinetic objectives of a generation of data, and proposed design vectors for the next GPR generation by searching for maximum expected improvement using local or global optimization algorithms.
The inputs required are the datafile containing desing parameters and objective values, the NMO yield and assembly-rate for the assembly condition/target, and the bounds for the GPR search.
We include as an example a GPR generation for HC assembly at \rho=0.53 using reflecting walls boundary condition.
The outputs of the code are optimized kernel parameters for the particular GPR generation; the next generation of proposed design vectors and their predicted objective values; the expected improvement for each value of lambda; and the averaged expected improvement.
