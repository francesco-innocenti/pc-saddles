# Only Strict Saddles in the Energy Landscape of Predictive Coding Networks?

![](https://github.com/francesco-innocenti/pc-saddles/blob/main/origin_saddle_toy_models.png)

* Code for the NeurIPS 2024 paper [Only Strict Saddles in the Energy Landscape of Predictive Coding Networks?](https://papers.nips.cc/paper_files/paper/2024/hash/6075fc6540b9a3cb951752099efd86ef-Abstract-Conference.html). 
* See [this blog post](https://francesco-innocenti.github.io/posts/2024/10/01/The-Energy-Landscape-of-Predictive-Coding-Networks/) for the key ideas of the paper. 
* Also check out [this library](https://github.com/thebuckleylab/jpc) for training predictive coding networks, which was used for some of the experiments in this paper.

# 💻 Reproducibility

All the results and plots from the paper can be reproduced from the included notebooks. All notebooks except for the convergence experiments can be run in < 15min on a CPU. For the heavier convergence experiments, we recommend using a GPU.

* Figure 1: [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/francesco-innocenti/pc-saddles/blob/main/Theoretical_Equilibrated_Energy.ipynb)
* For the toy examples in Figure 2 (and the statistics in Figure 7): [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/francesco-innocenti/pc-saddles/blob/main/Linear_Chains_Analysis.ipynb) & [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/francesco-innocenti/pc-saddles/blob/main/Hessian_Analysis_of_DLNs.ipynb)
* Figures 3-4 as well as 8-10: [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/francesco-innocenti/pc-saddles/blob/main/Hessian_Analysis_of_DLNs.ipynb)
* Figure 5 as well as 11-12: [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/francesco-innocenti/pc-saddles/blob/main/PC_vs_BP_Convergence_Experiments_on_DNNs.ipynb)
* Figure 6: [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/francesco-innocenti/pc-saddles/blob/main/Matrix_Completion_Experiment.ipynb)

## 📄 Citation
If you found this code useful in your work, please cite the paper:

```bibtex
@article{innocenti2025only,
  title={Only Strict Saddles in the Energy Landscape of Predictive Coding Networks?},
  author={Innocenti, Francesco and Achour, El Mehdi and Singh, Ryan and Buckley, Christopher L},
  journal={Advances in Neural Information Processing Systems},
  volume={37},
  pages={53649--53683},
  year={2025}
}
```
