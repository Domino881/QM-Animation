# Quantum Mechanics animations (personal project)

This code works by first finding the eigensystem of the unitless Hamiltonian
operator $$H=~-\nabla^2+V,$$
with $\nabla^2$ implemented using the second-order central difference method.

An initial state is then prepared and at each frame decomposed back into energy eigenstates, which evolve simply by an oscillating phase
$\psi_n(t)=e^{E_n/\hbar \cdot t}\psi_n$, and recomposed for plotting.

Example 1D animation:

![animation1d](https://github.com/Domino881/QM-Animation/blob/main/anim.gif)

Example 2D animation:

![animation2d](https://github.com/Domino881/QM-Animation/blob/main/anim2d.gif)
