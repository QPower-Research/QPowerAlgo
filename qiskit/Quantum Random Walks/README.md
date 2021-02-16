Quantum walks are the quantum variation of the well known random walks heavily used in computer science in many of its fields, one pretty famous example is the *Page Rank* algorithm, which can be generally seen as a walker on web pages that wants to rank which pages are the most relevant within an specific set of pages. 

Then in constrast to the classical random walk, where the walker occupies definite states and the randomness arises due to stochastic transitions between states, in quantum walks randomness arises throughout some properties from quantum mechanics like quantum superposition of states, non-randomness, reversible unitary evolution and collapse of the wave function due to state measurements.

It is pretty used in randomized algorithms, and are part of several quantum algorithms, as the Grover's search algorithm, which can be seen as a quantum walk algorithm.

Mathematically we can see the Quantum Walks, or more specifically Continuous-Time Quantum Walks in graphs, like a transition operator from a initial state to a state $t$, which is given by $U(t)$, defined as

$$U(t) = e^{itH}$$

This formulation comes from a solution to the Schrödinger’s equation, where $t$ defines our time and $H$ describes our Hamiltonian, which for the purpose of this work will be given by the graph adjacency matrix $A$.

# Continuous Time Quantum Walks

Finally we can define our continuous-time quantum walk by the unitary operator $U(t)$ on $G_n$ at time $t \geq 0$ as the following

$$U_{G_n}(t) = e^{-itA_{G_n}} \equiv \sum_{k = 0}^{\infty}\frac{(it)^k}{k!}A_{G_n}^k$$

And given a state $|\psi_{G_n, t}\rangle$ is the probability amplitude of each vertice at time $t$ is given by 

$$|\psi_{Gn, t}\rangle = U_{G_n}(t)|\psi_{G_n, 0}\rangle$$

Where the probability that the walker on $G_n$ is in position $x \in V(G)$ at time $t$ with initial state $|\psi_{G_n, 0}\rangle$ is

$$\mathcal{P}(x) = \big|U_{G_n}(t)|\psi_{G_n, 0}\rangle(x)\big|^2$$

# Discrete Time Quantum Walks

![Discrete Random Walks]()
