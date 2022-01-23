# Introduction
This project is to study the optical response in inversion-symmetry-breaking superconductors.

# Method
To simplify our simulation, we build our model based on a 1D supercell chain and figure out the Hamiltonian for it. A factor called `Δ_z` is used in the expression for Hamiltonian to control the symmetry. When `Δ_z` is assigned a nonzero value, the inversion symmetry will be broken.

We use tools from QuTiP to solve the Schrodinger equation for this system to get the eigenenergies and eigenfunctions. Then we can plot the band structures using eigenvalues and calculate the linear optical response.
# Reference
- Xu, T., Morimoto, T., & Moore, J. E. (2019). Nonlinear optical effects in inversion-symmetry-breaking superconductors. Physical Review B, 100(22), 220501.
