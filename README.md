# Quantum-Visualisation
This project aims to offer a visualisation tool for different simple problems in Quantum Mechanics. It offers plots the square of the wave functions of the energy eigenstates in such problems and also animation to show the time evolution of the probability densitiy for the position for superposed states (as the time evolution of the energy eigesntates is trivial, they are stationary states).
## Square Well Potential
The first problem analysed in this project was the Square Well potential. The problem was done in 1 dimension and in 2 dimensions.

This problem is defined as follows, we have a particle subject to a potential that is zero in the region 0x<L (and 0<y<L in 2D) and infinite everywhere else.
Basically the particle is trapped in the region with side L. We want to know the Energy Eigenstates wave functions (all allowed states can be expressed as a linear superposition of those states). To do so we solve the Scrodinger's Equation for this particula potential. This gives a well known solution for the wave functions of the different energy eigesntates (states with different defined energy). One of the postulates of Quantum Mechanics tells us that any state can be expressed as the linear superposition of the energy eigenstates. While the time evolution of the Energy eigenstates is trivial (there is only a phase change), it is not the case for the general sperposition of this states (as each of the states in the superposition evolves with a phase factor the overall result is non trivial in the superposition). To show this an animation of the time evolution of a superposed state (with coefficients of expansion given to the program) was created. All the results were interpreted in terms of the square of the wave function, which gives the porbability density function for the spatial coordinates.
### 1 Dimension
The following figure shows an example of the square of the wave function in the state n= 20
![This is an image](/Results/Square1DN=20.png)

The following figure shows the time evolution of the square of the wave function of an state that is the superposition of the first 20 excited states (all with equal probability).

![Alt Text](/Results/Square1D20States.gif)

## Harmonic Potential
The second problem analyzed in this project was the Harmonic Potential. The problem was done again for 1 and 2 dimensions.

The definition of this problem is similar to the first one, but in this case the potential V(x) is equal to the harmonic potential V(x) = kx^2. The problem was anaylized in a similar way than the first one. Firstly, the square of the wave functions of the energy eigesntates were obtained from the Schrodinger's equation (there is a numerical answer for each energy level in both 1D and 2D) and plots were made. Secondly animations of the time evolution of some special initial states were created by the decompisition of the initial wave functions into the superposition of energy eigenfunctions.
The following figure shows an example of the square of the wave function in the state n= 30

![Alt Text](/Results/Harmonic1DN=30.png)

The following figure shows the time evolution of the square of the wave function of an stat that has as initial wave function the dirac delta function:

![Alt Text](/Results/Harmonic1DDelta.gif)
