# Only Strict Saddles in the Energy Landscape of Predictive Coding Networks?

![](https://github.com/francesco-innocenti/pc-saddles/blob/main/origin_saddle_toy_models.png)

This repo has code for NeurIPS 2024 paper [Only Strict Saddles in the Energy Landscape of Predictive Coding Networks?](https://arxiv.org/abs/2408.11979). 
You can read [my blog post](https://francesco-innocenti.github.io/posts/2024/10/01/The-Energy-Landscape-of-Predictive-Coding-Networks/) for the key ideas of the paper. 

# Instructions

All the results and plots from the paper can be reproduced from the included notebooks. All notebooks except for the convergence experiments can be run in reasonable time (< 15min) on a CPU. For the heavier convergence experiments, we recommend using a GPU.

* To reproduce Figure 1, run `Theoretical_Equilibrated_Energy.ipynb`.
* To reproduce the toy examples in Figure 2 (and the statistics in Figure 7), run `Linear_Chains_Analysis.ipynb` and `Hessian_Analysis_of_DLNs.ipynb`.
* To reproduce Figure 3 & 4 (as well as 8-10), run `Hessian_Analysis_of_DLNs.ipynb`.
* To reproduce Figure 5 (as well as 11-12), run `PC_vs_BP_Convergence_Experiments_on_DNNs.ipynb`.
* Finally, to reproduce Figure 6, run `Matrix_Completion_Experiment.ipynb`.
