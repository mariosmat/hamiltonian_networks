
**Hamiltonian Neural Networks for Solving Differential Equations.**

These Hamiltonian Neural Networks is an alternative way to solve differential equations. This is a equation-driven unsupervised method since no data are used during the training of the network. For more information check the papers:

**arXiv:1904.08991** : Physical Symmetries Embedded in Neural Networks 

**arXiv:2001.11107** : Hamiltonian Neural Networks for solving differential equations  



**Basic Usage**
Simply run the python codes, as:

> python HamiltonianNet_nonlinearOscillator

> python HamiltonianNet_HenonHeiles



**Description**
Here, there are two python codes that include Hamiltonian neural networks used for solving differential equations that govern the spatio-temporal motion of dynamical systems. Two particular examples are presented by those codes. The nonlinear oscillator and the chaotic Henon-Heiles dynamical system. For comparison, a Scipy solver is used and its solutions are considered as the ground truth. In addition, an Euler symplectic integrator is used. The solutions obtained by the Hamiltonian neural network conserve the energy better than the solutions obtained by the symplectic Euler. 

You can investigate different activation functions and parametric solutions. Check for the comments # Define the Activation and # parametric solutions, respectively.

 After running the python codes (by reproducible run) figures will be saved. More specifically:

In nonlinear oscillator: (a) A figure with the training loss as a function of the training epochs; (b) The predicted trajectories x(t), y(t), the energy in time E(t), and the phase space trajectory p(x); (c) The errors of the predicted solutions delta_x(t), delta_p(t), the phase space error delta_p(delta_x), and again the energy in time.

In Henon-Heiles:  (a) A figure with the training loss as a function of the training epochs; (b) The  predicted trajectories x(t), y(t), the energy in time E(t),  and the orbit in x-y plane y(x).
