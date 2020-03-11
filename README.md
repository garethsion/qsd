# Quantum Spin Dynamics Simulation Linker

This repository contains methods which allow for the efficient simulation of superconducting microwave resonators for the purpose of electron spin resonance. Key figures of merit are calculated, including the resonators B0 field, Purcell enhancement, and pi pulse fidelity.

In order to determine these figures, it is necessary to run simulations in COMSOl multiphysics. To streamline the process, this package includes an ssh handling program, which links to remote machines, remotely runs simulations based on user parameter input, and returns the data to the host machine.

Documentation for this project can be found at https://qsd.readthedocs.io/
