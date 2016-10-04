 [![Creative Commons License](http://mirrors.creativecommons.org/presskit/logos/cc.logo.png)](http://creativecommons.org/
    licenses/by-nc-nd/4.0/)

# Applied Mathematics: an Introduction to Scientific Computing

- Luca Heltai (<luca.heltai@sissa.it>)
- Gianluigi Rozza (<gianluigi.rozza@sissa.it>)

## Syllabus 2016-2017

Frontal Lectures (about 24h), Interleaved with Laboratories (about 24h): total 48h, 6 CFU

### Frontal Lectures

##### Review Lectures
- Basic concepts of Vector spaces and norms
- Well posedness, condition numbers, Lax Richtmyer theorem
- Polynomial based approximations (Lagrange interpolation, Bernstein polynomials, Bsplines approximations)
- Quadrature rules and orthogonal polynomials
- Solution methods for Linear Systems: direct, iterative and least square methods
- Eigenvalues/Eigenvectors
- Solution methods for non-Linear systems
- Review of ODEs
- Review of FEM/Lax Milgram Lemma/Cea's Lemma/Error estimates
- High order methods/high continuity methods

##### Mathematical Modeling
- Data assimilation in biomechanics, statistics, medicine, electric signals
- Model order reduction of matrices
- Linear models for hydraulics, networks, logistics
- State equations (real gases), applied mechanics systems, grow population models, financial problems
- Applications of ODEs
- example in electric phenomena, signals and dynamics of populations (Lotke-Volterra)
- Models for prey-predator, population dynamics, automatic controls
- Applications of PDEs, the poisson problem
 - Elastic rope
 - Bar under traction
 - Heat conductivity
 - Maxwell equation

##### Advanced Numerical Methods and Models
A short introduction on a selection of following topics:

- Non conforming Finite Element Methods
- Mixed Finite Element Methods
- Darcy's equation
- Stokes

### Laboratories

##### Introductory lectures
- Introduction to Python, Numpy, Scipy
- Exercise on Condition numbers, interpolation, quadratures
- Using numpy for polynomial approximation
- Using numpy for numerical integration
- Using numpy/scipy for ODEs
- Working with numpy arrays, matrices and nd-arrays
- Solving non-linear systems of equations

##### Advanced lectures
- Object oriented programming in numerical analysis
- Review of best practices in programming for numerical analysis
- Working project: ePICURE (Python Isogeometric CUrve REconstruction)
- Solution of one dimensional PDEs using Finite Elements
- From one dimensional FEM to N-dimensional exploiting tensor structure of certain finite elements

##### Students projects
- Application of the Finite Element Method to the solution of models taken from the course

# Instructions for git aware students (and [MHPC](http://www.mhpc.it) students)

This repository contains, assignements, workspaces, and other material for the
course P1.4

New material will be uploaded frequently,

Remember to set a second remote, either to our private seed


	git remote add P1.4_seed https://github.com/sissa/P1.4_seed.git

or (if using ssh keys in your github account)

	git remote add P1.4_seed git@github.com:sissa/P1.4_seed.git

or to our public seed

	git remote add P1.4_seed https://github.com/luca-heltai/applied-mathematics.git

and to update before the lectures:

	git pull P1.4_seed master

**Please consider contributing pull requests to correct typos, or better document the material in this repository!**

# Licencing

The content of this repository is distributed with a Creative Common licence. See
the file LICENCE.md in this directory for more information.

# Attribution

Some of the material in this repository was adapted from the python-lectures by [Robert Johansson](https://github.com/jrjohansson/scientific-python-lectures). Take a look at his repository for additional material and lectures.

