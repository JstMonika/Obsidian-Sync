1. $\color{yellow}\mathcal{A}$ : Input tree set (called profile)
2. $\color{yellow}L(T_i) = S_i$ : Leaf set of $T$ 
3. $\color{yellow}V(T)$ : Vertices of $T$
4. $\color{yellow}E(T)$ : Edges of $T$
5. <span style="color:yellow"><i>refinement</i></span> : A tree $T'$ is a refinement of $T$ iff $T$ can be obtained from $T'$ by contracting a set of edges.
6. $\color{yellow}\pi_e := [A\>|\>B]$ : bipartition defined by edge $e$
7. $\color{yellow}C(T) := \{\pi_e\>|\>e\in E(T)\}$ : bipartition set on tree $T$
8. $\color{yellow}C(T_1, T_2, X) = C(T_1|_X) \cup C(T_2|_X)$
9. $\color{yellow}t|_X$ : the homeomorphic subtree of $t$ induced by $X$
10. $\color{yellow}\mathcal{T}_S$ : the set of all phylogenetic trees such that $L(T) = S$
11. $\color{yellow}\mathcal{T}_S^B$ : the binary trees in $\mathcal{T}_S$
12. $\color{yellow}P(e)$ : the path associated to edge $e$
13. $\color{yellow}w(e) :=|P(e)|$
14. $\color{yellow}e_i(\pi)$ : the edge that induces $\pi$ in $T_i|_X$
15. $\color{yellow}Extra(T_i)$ $= \{\text{t | t is a component in }T_i - T_i|_X\}$ 
16. $\color{yellow}T_{init}$ : a center root that adjacent to every $x \in X$ and also to the root $r(t)$ for every extra subtree $t \in Extra(T_1) \cup Extra(T_2)$
17. $\color{yellow}\mathcal{TR}(e)$ : the set of such extra subtrees attached to edge $e$
18. $\color{yellow}\mathcal{TR}^*(\pi)$ : the set of extra subtrees that attach to edges in a <span style='color:red'>backbone tree(?)</span> that induce $\pi$ in either $T_1|_X$ or $T_2|_X$
19. $\color{yellow}\mathcal{BP}_i(Q)$ : the set of bipartitions in $C(T_i|_X)$ that have one side being strict subset of $Q$.
20. $\color{yellow}\mathcal{TRS}_i(Q) := \cup_{\pi \in \mathcal{BP}_i(Q)}\mathcal{TR}(e_i(\pi))$ : the set of extra subtrees in $T_i$ that are "on the side of $Q$"
21. $\color{yellow}\Pi_1 = \{[A|B] \in \mathcal{C} | A \cap X \neq \emptyset \text{ and } B \cap X \neq \emptyset\}$ : the set of bipartitions from the input trees that are induced by edges in the minimal subtree of $T_1$ or $T_2$ spanning $X$. $\color{yellow}\Pi_2$ are all the other input tree bipartitions.
22. 