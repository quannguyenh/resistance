# resistance

Dependences:
- java 8+
- matrix-toolkits-java

Description:
The code in this repository provides the below utilities:
- to compute spectral values of graph edges
- to sort edges based on their resistance value
- to perform three types of graph sampling.

- Random edge is a sampling method in which edges are chosen at random.
- DSS and SSS are sampling methods which choosing edges based on their resistance value.
- DSS rank the edges from highest to lowest value of resistance and then chose edges in the order.
- SSS chose an edge with the probability that is proportional to the resistance value of the edge.

If you use this code, please cite the paper "Drawing Big Graphs using Spectral Sparsification", Graph Drawing 2017.
https://link.springer.com/chapter/10.1007/978-3-319-73915-1_22


