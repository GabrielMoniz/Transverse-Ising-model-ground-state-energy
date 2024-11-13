# Transverse-Ising-model-ground-state-energy
My attempt to create a code the provides the ground state energy for transverse ising model using pennylane based on the following problem for the Hackathon challenge in Second Quantum Computing School at ICTP-SAIRF,
however here I aim to generalize for arbitrary number of particles N.

 Consider a spin chain consisting of N spin - 1/2 particles, where each spin can point
either in the positive or negative z-direction. Additionally, an external magnetic field is
applied to the system.
This quantum system is described by the Transverse Ising Hamiltonian. For a closed
spin chain with a transverse magnetic field of intensity h, the Hamiltonian is:

$$H = − \sum_{i=1}^N Z_i \otimes Z_{i+1} − h\sum_{i=1}^N X_i\ ,$$


where $Z_i$ and $X_i$ are the Pauli-Z and Pauli-X operators acting on the i-th spin site,
respectively. In a closed chain, the site N + 1 is identified with the first site.

You must implement a variational quantum algorithm in Pennylane that, for a given
value of the transverse magnetic field h, computes the ground state energy of the spin
chain with N=4 sites. The magnetic field intensity h should be passed as an input to
the algorithm.
