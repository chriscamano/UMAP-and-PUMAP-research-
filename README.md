# UMAP-and-PUMAP-research-

This repository of the research and development log of work on the Uniform Manifold Approximate Projection method (UMAP). Special emphasis placed on exploring the underyling 
behavior of UMAP and other dimensionality reduction schemes in the presence of symmetry augmentations in the input space. This research is a continuation of a generalized exploration into dimensionality reduction schemes started in the Spring of 2021. For information about that research such as past notebooks, figures, or experimental data please reach out to me for a copy. 

This work is funded by the CSU-LSAMP-NSF research grant,Explore CSR, CAHSI-REU, and San Francisco State University under the guidance of Dr. Daniel Huang.

# Research Resources: 

### 🔵𝗪𝗲𝗲𝗸 #𝟭: 

**[1] On UMAP's true loss function**

 > _Original paper:_                        https://arxiv.org/abs/2103.14608

 > _Supplemental Power point presentation_: https://openreview.net/forum?id=DKRcikndMGC

 > _Peer review comments_ :                 https://neurips.cc/media/neurips-2021/Slides/28679.pdf
 
 > _Github Implementation_ :                https://github.com/hci-unihd/UMAPs-true-loss

**[2] A Unifying Perspective on Neighbor Embeddings along the Attraction-Repulsion Spectrum**

 > _Original Paper_                         https://arxiv.org/pdf/2007.08902.pdf

**[3] GiDR-DUN; Gradient Dimensionality Reduction** - Differences and Unification (TSNE UMAP hybrid algorithm)

 > _Original Paper_ :                       https://www.semanticscholar.org/paper/Initialization-is-critical-for-preserving-global-in-Kobak-Linderman/d1fb7e7e88168347ed6e8a06b8227ab88d26ed8a

### 🔵𝗪𝗲𝗲𝗸 #2: 

**Powerpoint Recap:** https://docs.google.com/presentation/d/1_z6uxcg5dpM57YKzehbv9SCh4gnkPNuwvJTYPZhOXOA/edit?usp=sharing

**[1] Discussion of rotational invariance within the P-UMAP algorithm. Done through feeding loss back into the network and optimizing**

> _Original Paper_:                         https://arxiv.org/abs/2009.12981v2?sid=SCITRUS

**[2] Anti-Alising correcting Rotation through decomposition to shear transformations**

> _Original Paper_:                         https://link.springer.com/content/pdf/10.1007/3-540-62005-2_26.pdf

> _Additional resources for algorithm :     https://www.ocf.berkeley.edu/~fricke/projects/israel/paeth/rotation_by_shearing.html

**[3] Higher dimensional rotation schemes**

> _Original Paper_:                         https://core.ac.uk/download/pdf/295553405.pdf

**[4] Running UMAP on GPU using RAPIDS environment**

> _Link_:                                   https://medium.com/the-artificial-impostor/umap-on-rapids-15x-speedup-f4eabfbdd978

> _Rapids website and info_:                https://rapids.ai/start.html

### 🔵𝗪𝗲𝗲𝗸 #3:

**Powerpoint Recap: https://docs.google.com/presentation/d/1lFPLMPbLZruR6GWnJ7O5a6cUS2TTLBeogsLlUnRvHrI/edit?usp=sharing**

**[1] Eliminating Topological Errors in Neural Network Rotation Estimation
Using Self-selecting Ensembles (The main paper currently)⭐**

> _Original paper_:                   https://vgl.ict.usc.edu/Research/NNRE/Eliminating%20Topological%20Errors%20in%20Neural%20Network%20Rotation%20Estimation%20Using%20Self-selecting%20Ensembles.pdf

**[2] SVD based image rotation estimation scheme**

> _Original paper_:                         https://arxiv.org/pdf/2006.14616.pdf

**[3] Image classification schemes investigated for rotation correction (dead end)**

> _Original Paper_:                         https://arxiv.org/ftp/arxiv/papers/1904/1904.06554.pdf

### 🔵𝗪𝗲𝗲𝗸 #4 and #5:

**[1] Learning SO(3) Equivariant Representations**
with Spherical CNNs

> _Original Paper_ :                        https://arxiv.org/pdf/1711.06721.pdf

**[2] Kabash Algorithm**

> _Wikipedia page_:                         https://en.wikipedia.org/wiki/Kabsch_algorithm

> _Original paper(1976!)_:                         https://sci-hub.se/10.1107/s0567739476001873

> _Theoretical motivation_:                 https://math.nist.gov/~JBernal/kujustf.pdf

> _Further analysis and connection to SVD:  https://igl.ethz.ch/projects/ARAP/svd_rot.pdf

> _Implentation example:                    https://gist.github.com/oshea00/dfb7d657feca009bf4d095d4cb8ea4be

**[3] Estimating 3-D Location Parameters Using Dual Number Quaternions** 

> _Original Paper_:                        https://sci-hub.se/10.1016/1049-9660%2891%2990036-o


