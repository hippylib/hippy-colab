# hippy-colab

Selected [hIPPYlib](https://hippylib.github.io/) notebooks on Google Colab.

hIPPYlib implements state-of-the-art scalable adjoint-based algorithms for PDE-based deterministic and Bayesian inverse problems. It builds on [FEniCS](https://fenicsproject.org/) for the discretization of the PDE and on [PETSc](https://petsc.org/release/) for scalable and efficient linear algebra operations and solvers.

These collection of notebook was prepared for our SIAM Annual Meeting Minitutorial on [Introduction to Bayesian Inverse Problems Governed by Partial Differential Equations (PDEs): A Hands-on Tutorial using hIPPYlib](https://meetings.siam.org/sess/dsp_talk.cfm?p=160239).

## Notebooks

1. Inverse problem prototype: An illustrative example of an ill-posed inverse problem. [(Colab)[https://colab.research.google.com/github/hippylib/hippy-colab/blob/main/01_inverseProblemPrototype.ipynb]]

## Useful References

### Theory and computational methods for inverse problems:

- Heinz Engl, Michael Hanke, and Andreas Neubauer, *Regularization of Inverse Problems*, Dordrecht, 2nd ed., 1996.

- Curtis R. Vogel, *Computational Methods for Inverse Problems*, SIAM, 2002.

- Guy Chavent, *Nonlinear Least Squares for Inverse Problems*, Springer, 2009.

- Omar Ghattas and Karen Willcox, *Learning physics-based models from data: perspectives from inverse problems and model reduction*, Acta Numerical, 2021.


### Numerical optimization background:

- Jorge Nocedal and Stephen J. Wright, *Numerical Optimization*, Springer-Verlag, 1999.

- C. Tim Kelley, *Iterative Methods of Optimization*, SIAM, 1999.

### Optimization of systems governed by PDEs:

- A. Borzi and V. Schulz, *Computational Optimization of Systems Governed by Partial Differential Equations*, SIAM, 2012.

- Fredi Tröltzsch, *Optimal Control of Partial Differential Equations: Theory, Methods and Applications*, Graduate Studies in Mathematics Vol.~112, AMS, 2010.

- M. Hinze, R. Pinnau, M. Ulbich, and S. Ulbrich, *Optimization with PDE constraints*, Springer, 2009.

- Alen Alexanderian, *Computational Inverse Problems Governed by PDEs*, SIAM 2026.

### Finite element background and FEniCS:
  
- Eric B. Becker, Graham F. Carey, and J. Tinsley Oden, *Finite Elements: Volume I, An Introduction*, Prentice Hall, 1981.

- Mark S. Gockenbach, *Understanding and Implementing the Finite Element Method*, SIAM, 2006.

- Howard Elman, David Silvester, and Andrew Wathen, *Finite Elements and Fast Iterative Solvers*, Oxford University Press, 2005.

- A. Logg, K. A. Mardal, and G. Wells, *Automated solution of differential equations by the finite element method: The FEniCS
  book*, vol. 84, Springer Science \& Business Media, 2012.

### Probabilistic approach to inverse problems:

- Albert Tarantola, *Inverse Problem Theory and Methods for Model Parameter Estimation*, SIAM, 2005.

- Jari Kaipio and Erkki Somersalo, *Statistical and Computational Inverse Problems*, Springer, 2005.

- Andrew Stuart, Inverse problems, *A Bayesian approach*, Acta Numerica, 2010.

- Daniela Calvetti and Erkki Somersalo, *Bayesian Scientific Computing*, Springer, 2023.

- Johnathan Bardsley, *Computational Uncertainty Quantification for Inverse Problems*, SIAM, 2018.




## Acknowledgements
The hIPPYlib project started in 2016 with initial support from the US National Science Foundation under awards ACI-1550593, ACI-1550547. 
