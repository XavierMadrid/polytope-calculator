# polytope-calculator

Hi! The following is very slightly math heavy. Be warned!

A polytope is the generalization of a polyhedron to n dimensions. That is to say, a line segment is a 1-dimensional polytope, a convex polygon is a two-dimensional polytope, a convex polyhedron is a 3-dimensional polytope, and so on. Quivers, in simple terms, is a directed graph G with a vector space attached to each vertex and a linear map to each edge in G. For our purposes, the vector spaces are one-dimensional (so each vertex has a single number attached, its weight) and the linear maps on each edge are defined by the linear map I_Q, defined in the papers attached at the end of this. By considering an element of the image of I_Q, we can consider its preimage, which happens to be a polytope if the quiver is acyclic. The scripts in this repository calculate such polytopes given a quiver input.

There are several papers on the topics discussed above. One important paper is given by [Hille 2003](https://www.sciencedirect.com/science/article/pii/S0024379502004068), which gives a good introduction of the topic (though it is still very math heavy). The second paper is a very comprehensive coverage of the topic given by [Domokos 2014](https://doi.org/10.48550/arXiv.1402.5096), which is very advanced.

I performed research on this topic during the 2023-2024 year at University of California, Riverside under a mathematics professor Patricio Candela-Gallardo, who cowrote the package ThinSincereQuivers for Macaualay2. I am currently writing a paper on the classifications and operations of the polytope associated with the canonical weight of a quiver. I used these scripts to calculate examples en masse to help generate conjectures and verify ideas.

Xavier Madrid
