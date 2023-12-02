## Introduction

1. [[RawNote#^jtppt97rdd|Supertree construction]]
	1. [[RawNote#^pfgo8cndh5|can be used as a final step in a divide-and-conquer pipeline]]
2. Same?
	1. provided that optimal supertrees are computed, divide-and-conquer pipelines can be provably statistically consistent under stochastic models of evolution
	2. as the amount of input data (e.g., sequence lengths when estimating gene trees, or number of gene trees when estimating species trees) increases, the probability that the true tree is returned converges to 1
3. [[RawNote#^pb5h17kpn1s|the NP-hard Maximum Agreement Supertree (SMAST) problem]]
	1. [[RawNote#^z7m7d42cu4|known as the Agreement Supertree Taxon Removalproblem]]
4. [[RawNote#^0ou8dessaki|Because SMAST and SMCT remove taxa]]
	1. [[RawNote#^m2eo63or9m|These optimization problem are not true supertree methods, because they do not return a tree on the entire set of taxa]]
	2. [[RawNote#^la41nrncuqm|could potentially be used as constraints for other supertreemethods]]
	3. [[RawNote#^928h53o4wh| is of interest]]
5. [[RawNote#^dpemdp53skq|MaximumAgreement Supertree Edge Contraction problem (which takes as input a set of rooted treesand seeks a minimum number of edges to collapse so that an agreement supertree exists).]]
6. [[RawNote#^d2gduaenn07|In sum, while supertree methods are important and well studied, when restricted to themajor optimization problems that do not remove taxa, polynomial time methods do notseem to be available, even for the special case where the input contains just two trees]]
7. 