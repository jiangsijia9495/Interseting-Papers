# Interesting Papers

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> An awesome & curated list of papers about 3D human body.

-----

## Table of Contents

- [SIREN](#SIREN)
- [NERF](#NERF)
- [Contrastive Learning](#contrastive-learning)
- [Recent Implicit Function Improvement](#recent-implicit-function-improvement)
- [Poisson Surface Reconstrction](#poisson-surface-reconstrction)
-----


## SIREN


###  CVPR


[Expressive Body Capture: 3D Hands, Face, and Body from a Single Image](https://ps.is.tuebingen.mpg.de/uploads_file/attachment/attachment/497/SMPL-X.pdf). CVPR, 2019. [[Page]](https://smpl-x.is.tue.mpg.de) [[Code]](https://github.com/vchoutas/smplify-x)

[GHUM & GHUML: Generative 3D Human Shape and Articulated Pose Models](https://arxiv.org/pdf/2008.08535). CVPR (Oral), 2020.  [[Code]](https://github.com/google-research/google-research/tree/master/ghum)

### ICCV
[Modulated Periodic Activations for Generalizable Local Functional Representations](https://cseweb.ucsd.edu/~ravir/ishit_iccv.pdf). ICCV, 2021.
   - **Abstract:** Recent works have significantly improved their ability to represent high-frequency content by using periodic activations or positional encodings. This often came at the expense of generalization: modern methods are typically optimized for a single signal. We present a new representation that generalizes to multiple instances and achieves state-of-the-art fidelity
   - **Inspiration:** 
     1. A simpler alternative to using a separate modulation network would be to concatenate the latent codes and the input coordinates, and use the resultant vector as a single input to the synthesis network. This strategy has shown to be fruitful for ReLU-based synthesis networks for encoding signed distance fields [32]. However, we find it consistently fails with sine activations.
     2.  Some recent work has explored locality, but they focus on relatively simple, low-frequency signals like signed distance fields [4, 13], which can locally be well approximated using a single linear decision boundary???

###  ECCV




###  SIGGRAPH(ASIA)/ToG




###  ArXiv


[NPMs: Neural Parametric Models for 3D Deformable Shapes](https://arxiv.org/abs/2104.00702). ArXiv, 2021. [[Page]](https://www.youtube.com/watch?v=muZXXgkkMPY) 


###  Others





## NERF

### ICCV

[UNISURF: Unifying Neural Implicit Surfaces and Radiance Fields for Multi-View Reconstruction](https://arxiv.org/abs/2104.10078) . ICCV, 2021. [[Code]](https://github.com/autonomousvision/unisurf)
   - **Abstract:** Unify surface rendering and volume rendering for implicit surfaces. DVR need mask. Nerf does not need mask but does not have clear threshold for surface.
   - 

### ArXiv

[KiloNeRF: Speeding up Neural Radiance Fields with Thousands of Tiny MLPs](https://arxiv.org/abs/2103.13744). ArXiv, 2021. [[Code]](https://github.com/creiser/kilonerf)






## Contrastive Learning

### ICML

[A Simple Framework for Contrastive Learning of Visual Representations](https://arxiv.org/pdf/2002.05709.pdf). ICML, 2020. [[Code]](https://github.com/google-research/simclr)


## Recent Implicit Function Improvement

### Differential Implicit Rendering
[Differentiable Volumetric Rendering:Learning Implicit 3D Representations without 3D Supervision](http://www.cvlibs.net/publications/Niemeyer2020CVPR.pdf). CVPR,2020. [[Code]](https://github.com/autonomousvision/differentiable_volumetric_rendering)

### Spatial Sampling
[Overfit neural networks as a compact shape representation](). , 2020. [[Code]]()

### training procedure
[Metasdf: Meta-learning signed distance functions](). , 2020. [[Code]]()

### loss functions
[Implicit geometric regularization for learning shapes](). , 2020. [[Code]]()


## Poisson Surface Reconstrction

[Shape As Points: A Differentiable Poisson Solver](https://arxiv.org/pdf/2106.03452.pdf). NeurIPS,2021.
   - **Inspiration:** 
     1. Use Differentiable Poisson Solver to generate indicator grid from ground truth mesh. This avoids running Marching Cubes at every iteration and accelerates training. 
     2.  s


-----

## [Back to Top](#table-of-contents)
