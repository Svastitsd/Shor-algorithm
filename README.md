# Shor-algorithm
The notebook contains a general implementation of Shor's factoring algorithm.
The algorithm can be tested using IBM's devices.
The circuits can't be run on a quantum computer since they are too long,
but they can be tested using the simulators for small N-s such as 15 and 21.
The Shor(N, cbits=3) function returns a list with the prime factors of N. 
The quantumcircuit generated by the function uses 2n+cbits controll qubits, where 
n is the bit length of N.
