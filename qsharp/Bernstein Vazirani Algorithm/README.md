The Bernstein-Vazirani algorithm can be seen as an extension of the Deutsch-Josza algorithm we covered in the last section.

It shows that there can be advantages in using a quantum computer as a computational tool for more complex problems, Quantum computing can go far beyond the possibilities of today’s classical high performance computing.

Suppose we have a black box, by it we mean we cannot get any information from it, there is a binary string in this box and we want to know the number.

With classical computer very time we can perform a single and operation on box and see the output result and finally get to know the number. But with a Quantum computer and by using Bernstein-Vazirani Algorithm we can know the number just with on operation.

In order to implement Bernstein-Vazirani Algorithm, we need to take few steps:

Initialise the inputs qubits to the |0> state, and output qubit to |->.

Apply Hadamard gates to the input register

Query the oracle

Apply Hadamard gates to the input register

Measure