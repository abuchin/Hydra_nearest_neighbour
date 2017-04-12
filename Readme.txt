Readme

The network is generated based on the given connectivity distribution taken from the experimental data. 
The algorithm generates the graph to match the given connectivity distribution under the geometric constrains
such as tube and nearest-neighbour assumption. The connectivity distribution is taken from the Dupre and Yuste paper (http://www.sciencedirect.com/science/article/pii/S0960982217302208), where they counted the number of the
neurite branches near the soma.

To generate the adjacency matrix of the graph use M_FullTube_prob_cut_add.m function
Examples of the generated graphs could be found in ./Reconstruction/FULLTUBE
