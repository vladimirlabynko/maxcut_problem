Generate random graph with n nodes where every node is connected
with k nodes (k<n). The weight of the edge is random in [0,1] interval. The
goal is to solve MaxCut problem with gnn (described
in https://github.com/amazon-science/co-with-gnns-example).
Fix n=40. Analyse the performance of the GNN with respect to k. What is
the optimality of GNN with the increase of k? Provide a plot of dependence
of E_found with respect to k. The real solution E_real can be found using
brute search. The optimality is |E_real-E_found|/|E_real|. Here E_found is
the objective value found by GNN and E_real is the real objective value.
