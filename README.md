[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/AtNXzL3S)
# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Two graphs are isomorphic if and only if they are one-to-one and onto each other. The onto part of this definition is what restricts the graphs from having a different number of nodes. The graphs must be onto,
so each node in G1 must correspond to a node in G2. It also is one-to-one, so each node can only map to one unique node in G2. Say that G1 has one more vertice than G2.
There will always be a node in G1 that is not mapped onto by G2, and we cannot map two nodes onto one node of G2 because of the one-to-one property, they must map to unique nodes.
Additionally, if G1 has another vertice, then there must be at least one edge connecting it to the graph. So G1 would also have at least one more edge than G2. This edge would also make isomorphism impossible 
because $\ (u,v) \in E_1 <=> (f(u), f(v)) \in E_2$ must also stand. If they have a different number of edges than there will be a (u, v) that cannot map onto a unique (f(u), f(v)) in G2.
