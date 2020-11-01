# QPowerAlgo

# Algorithms with the qiskit framework

## Bell States(Quantum Entanglement)
_add list here_

## Grover's Search
_add list here_

## Shor's Factorization
Shor’s algorithm is famous for factoring integers in polynomial time. Since the best-known classical algorithm requires superpolynomial time to factor the product of two primes, the widely used cryptosystem, RSA, relies on factoring being impossible for large enough integers.

The textbook link below contains more information about the algorithm, along with its implementation with Qiskit.

- [Qiskit Textbook](https://qiskit.org/textbook/ch-algorithms/shor.html)


## Quantum Key Distribution
Quantum key distribution (QKD) is a secure communication method which implements a cryptographic protocol involving components of quantum mechanics. It enables two parties to produce a shared random secret key known only to them, which can then be used to encrypt and decrypt messages. It is often incorrectly called quantum cryptography, as it is the best-known example of a quantum cryptographic task. By using quantum superpositions or quantum entanglement and transmitting information in quantum states, a communication system can be implemented that detects eavesdropping. If the level of eavesdropping is below a certain threshold, a key can be produced that is guaranteed to be secure (i.e., the eavesdropper has no information about it), otherwise no secure key is possible and communication is aborted.

Some great resources to understand the algorithm and implement with qiskit:

- [Qiskit Textbook](https://qiskit.org/textbook/ch-algorithms/quantum-key-distribution.html)
- [Wired](https://www.wired.com/insights/2014/09/quantum-key-distribution/)
- [Implementation](https://www.youtube.com/watch?v=hArTusF4KPg)


## Bernstein Vazirani Algorithm
The Bernstein–Vazirani algorithm, which solves the Bernstein–Vazirani problem is a quantum algorithm invented by Ethan Bernstein and Umesh Vazirani in 1992. It's a restricted version of the Deutsch–Jozsa algorithm where instead of distinguishing between two different classes of functions, it tries to learn a string encoded in a function. The Bernstein–Vazirani algorithm was designed to prove an oracle separation between complexity classes BQP and BPP.

Some great resources to understand the algorithm and implement with qiskit:

- [Qiskit Textbook](https://qiskit.org/textbook/ch-algorithms/bernstein-vazirani.html)
- [Medium](https://medium.com/@lana.bozanic/the-bernstein-vazirani-algorithm-9f5fc9d0518e)
- [Programming with Qiskit](https://www.youtube.com/watch?v=sqJIpHYl7oo)


## Deutsch-Jozsa Algorithm
The Deutsch-Jozsa algorithm was the first example of a quantum algorithm that performs better than the best classical algorithm. It showed that there can be advantages to using a quantum computer as a computational tool for a specific problem. 

The Deutsch-Josza algorithm is a simple example of a quantum algorithm that can be used to speed up a search. It determines whether or not a function has a certain property (balanced). The algorithm achieves this by requiring that the function need only be called once with a quantum algorithm instead of twice with a classical algorithm. When the function is very 'expensive', e.g., in terms of computational resources, it can be very beneficial if you have to compute this function only once instead of twice.

Although the speed-up of this specific algorithm is only a factor of 2, other quantum algorithms, using the same quantum mechanical effects, can achieve a polynomial or even an exponential speed-up compared to classical algorithms.

Some great resources to understand the algorithm and implement with qiskit:
- [Qiskit Textbook](https://qiskit.org/textbook/ch-algorithms/deutsch-jozsa.html)
- [Medium](https://www.quantum-inspire.com/kbase/deutsch-jozsa-algorithm/)
- [Deutsch Algorithm Explained](https://www.youtube.com/watch?v=5xsyx-aNClM)
- [Deutsch Algorithm w/ Qiskit Walkthrough](https://www.youtube.com/watch?v=_BHvE_pwF6E&list=PLQVvvaa0QuDc79w6NcGB0pnoJBgaKdfrW&index=3)


## Quantum Teleportation

Quantum teleportation is a demonstration of what Albert Einstein famously called "spooky action at a distance"—also known as quantum entanglement. In entanglement—one of the basic of concepts of quantum physics—the properties of one particle affect the properties of another, even when the particles are separated by a large distance. Quantum teleportation involves two distant, entangled particles in which the state of a third particle instantly "teleports" its state to the two entangled particles.

Quantum teleportation is an important means for transmitting information in quantum computing. While a typical computer consists of billions of transistors, called bits, quantum computers encode information in quantum bits, or qubits. A bit has a single binary value, which can be either "0" or "1," but qubits can be both "0" and "1" at the same time. The ability for individual qubits to simultaneously occupy multiple states underlies the great potential power of quantum computers.

Some great resources to understand and implement with qiskit:
- [Qiskit Textbook on Teleportation](https://qiskit.org/textbook/ch-algorithms/teleportation.html)
- [Medium article on Teleportation](https://medium.com/qiskit/untangling-quantum-teleportation-919cbd673074)
- [Quantum Teleportation Programming with Qiskit](https://www.youtube.com/watch?v=mMwovHK2NrE)
- [Quantum Teleportation explained with No Cloning Theory (short)](https://www.youtube.com/watch?v=AbmH1xTn2N0)
- [Quantum Teleportation explained (long)](https://www.youtube.com/watch?v=3nburCsAnmo)

## VQC(Variational Quantum Classifier)
_add list here_

## Other
_add list here_
