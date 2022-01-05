# Quantum-Visualisation
This project aims to offer a visualisation of the wave functions of the Energy Eigenstates for a Quantum Harmonic Oscillator using Mathematica. 
## Square Well Potential
The first problem analysed in this project was the Square Well potential. The problem was done in 1 dimension and in 2 dimensions.

This problem is defined as follows, we have a particle subject to a potential that is zero in the region 0x<L (and 0<y<L in 2D) and infinite everywhere else.
Basically the particle is trapped in the region with side L. We want to know the Energy Eigenstates wave functions (all allowed states can be expressed as a linear superposition of those states). To do so we solve the Scrodinger's Equation for this particula potential. This gives a well known solution for the wave functions of the different energy eigesntates (states with different defined energy). One of the postulates of Quantum Mechanics tells us that any state can be expressed as the linear superposition of the energy eigenstates. While the time evolution of the Energy eigenstates is trivial (there is only a phase change), it is not the case for the general sperposition of this states (as each of the states in the superposition evolves with a phase factor the overall result is non trivial in the superposition). To show this an animation of the time evolution of a superposed state (with coefficients of expansion given to the program) was created. All the results were interpreted in terms of the square of the wave function, which gives the porbability density function for the spatial coordinates.
### 1 Dimension
The following figure shows an example of the square of the wave function in the state n= 30
![This is an image](/Results/Harmonic1DN=30.png)

The following figure shows the time evolution of the square of the wave function of an state that is the superposition of the first 20 excited states (all with equal probability).
