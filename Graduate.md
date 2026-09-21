# Graduate-Level Applied Mathematics Curriculum & Self-Study Roadmap

This curriculum bridges foundational applied mathematics with graduate-level research tools. It organizes into three overarching tiers: **The Analytic & Functional Core**, **Differential Equations & Variational Frameworks**, and **Scientific Computing, Optimization & Stochastics**.

---

## Tier 1: The Analytic & Functional Core

### 1. Real Analysis, Measure Theory & Integration
* **Focus:** $\sigma$-algebras, Carathéodory extension theorem, Lebesgue measure on $\mathbb{R}^n$, convergence theorems (MCT, DCT, Fatou), product measures, Fubini-Tonelli theorems, signed measures, Radon-Nikodym derivative, and $L^p$ space completeness and duality.
* **Course Resource:** [MIT OCW 18.125 Measure and Integration](https://ocw.mit.edu/courses/18-125-measure-and-integration-fall-2003/)
* **Textbooks & Exercises:**
  * *Real Analysis: Modern Techniques and Their Applications* by Gerald B. Folland.
  * *Real and Complex Analysis* by Walter Rudin (Chapters 1–8).

### 2. Applied Functional Analysis
* **Focus:** Banach and Hilbert spaces, bounded linear operators, dual spaces, Hahn-Banach theorem, Open Mapping and Closed Graph theorems, weak and weak-* topologies, reflexive spaces, compact operators, and Fredholm alternative.
* **Course Resource:** [MIT OCW 18.102 Introduction to Functional Analysis](https://ocw.mit.edu/courses/18-102-introduction-to-functional-analysis-spring-2021/)
* **Textbooks & Exercises:**
  * *Functional Analysis, Sobolev Spaces and Partial Differential Equations* by Haim Brezis.
  * *Applied Analysis* by John K. Hunter and Bruno Nachtergaele.

### 3. Spectral Theory & Operator Algebras
* **Focus:** Resolvent sets, spectrum of bounded/unbounded self-adjoint operators, spectral theorem for bounded and unbounded operators, projection-valued measures, and semigroups of linear operators ($C_0$-semigroups, Hille-Yosida theorem).
* **Textbook & Exercises:** *Methods of Modern Mathematical Physics, Vol. 1: Functional Analysis* by Michael Reed and Barry Simon.

---

## Tier 2: Differential Equations & Variational Frameworks

### 4. Advanced Partial Differential Equations (Modern PDE Theory)
* **Focus:** Weak derivatives, Sobolev spaces ($W^{k,p}$ and $H^s$), trace theorems, Sobolev embedding theorems, Poincaré inequalities, Lax-Milgram theorem, weak solutions to second-order elliptic equations, parabolic and hyperbolic systems, and maximum principles.
* **Course Resource:** [MIT OCW 18.152 Introduction to Partial Differential Equations](https://ocw.mit.edu/courses/18-152-introduction-to-partial-differential-equations-fall-2011/)
* **Textbooks & Exercises:**
  * *Partial Differential Equations* (Graduate Studies in Mathematics) by Lawrence C. Evans (the standard doctoral reference).
  * *Elliptic Partial Differential Equations of Second Order* by David Gilbarg and Neil S. Trudinger.

### 5. Calculus of Variations & Geometric Measure Theory Basics
* **Focus:** Direct method in the calculus of variations, Euler-Lagrange equations, weak lower semicontinuity, coercivity, constrained variational problems, min-max methods, $\Gamma$-convergence, and introduction to currents and perimeter.
* **Textbooks & Exercises:**
  * *Direct Methods in the Calculus of Variations* by Enrico Giusti.
  * *Calculus of Variations* by Filip Rindler.

### 6. Nonlinear Dynamics, Bifurcation Theory & Ergodic Theory
* **Focus:** Center manifold theorem, normal forms, local and global bifurcations (Hopf, saddle-node, homoclinic), invariant manifolds, Lyapunov exponents, Hamiltonian mechanics, Symplectic geometry basics, and measure-preserving dynamical systems.
* **Textbooks & Exercises:**
  * *Nonlinear Oscillations, Dynamical Systems, and Bifurcations of Vector Fields* by John Guckenheimer and Philip Holmes.
  * *Introduction to the Modern Theory of Dynamical Systems* by Anatole Katok and Boris Hasselblatt.

---

## Tier 3: Scientific Computing, Optimization & Stochastics

### 7. Numerical Analysis of PDEs & Finite Element Methods (FEM)
* **Focus:** Variational/weak formulation of boundary value problems, Céa's lemma, Galerkin approximations, polynomial interpolation in Sobolev spaces, error estimates, a posteriori error estimators, adaptive mesh refinement, and domain decomposition.
* **Textbooks & Exercises:**
  * *The Mathematical Theory of Finite Element Methods* by Susanne C. Brenner and L. Ridgway Scott.
  * *Numerical Approximation of Partial Differential Equations* by Alfio Quarteroni and Alberto Valli.

### 8. Numerical Linear Algebra & High-Performance Solvers
* **Focus:** Perturbation theory, backward error analysis, Krylov subspace methods (Conjugate Gradient, GMRES, BiCGSTAB), Arnoldi/Lanczos iterations, preconditioning strategies, multigrid methods (algebraic and geometric), and randomized numerical linear algebra (RandNLA).
* **Course Resource:** [MIT OCW 18.335J Introduction to Numerical Methods](https://ocw.mit.edu/courses/18-335j-introduction-to-numerical-methods-spring-2019/)
* **Textbooks & Exercises:**
  * *Numerical Linear Algebra* by Lloyd N. Trefethen and David Bau III.
  * *Iterative Methods for Sparse Linear Systems* by Yousef Saad.

### 9. Continuous, Convex & Non-Convex Optimization
* **Focus:** Subgradient calculus, Fenchel-Rockafellar duality, proximal operators and ADMM, interior point methods, first-order accelerated schemes (Nesterov acceleration), stochastic gradient algorithms, and non-convex landscape analysis.
* **Course Resource:** [Stanford EE364b Convex Optimization II](https://web.stanford.edu/class/ee364b/)
* **Textbooks & Exercises:**
  * *Convex Optimization* by Stephen Boyd and Lieven Vandenberghe.
  * *First-Order Methods in Optimization* by Amir Beck.
  * *Lectures on Convex Optimization* by Yurii Nesterov.

### 10. Measure-Theoretic Probability & Stochastic Calculus
* **Focus:** Conditional expectation with respect to $\sigma$-algebras, discrete and continuous-time martingales, Doob’s optional stopping, stopping times, Brownian motion construction and sample path properties, Itô integrals, Itô’s lemma, Girsanov theorem, Stochastic Differential Equations (SDEs), and Feynman-Kac formula.
* **Textbooks & Exercises:**
  * *Probability: Theory and Examples* by Rick Durrett.
  * *Brownian Motion and Stochastic Calculus* by Ioannis Karatzas and Steven E. Shreve.
  * *Stochastic Differential Equations: An Introduction with Applications* by Bernt Øksendal.

### 11. Optimal Transport & Applied Probability
* **Focus:** Monge and Kantorovich formulations, Wasserstein distances ($W_1, W_2$), Brenier’s theorem, Benamou-Brenier dynamic formulation, displacement interpolation, entropic regularization, Sinkhorn algorithm, and applications to PDEs and generative modeling.
* **Textbooks & Exercises:**
  * *Optimal Transport: Old and New* by Cédric Villani.
  * *Computational Optimal Transport* by Gabriel Peyré and Marco Cuturi (focuses on fast computational implementation).
