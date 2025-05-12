# Numerical-Methods-For-PDEs

Partial Differential Equations are ubiquitous throughout Math, Science, and Engineering. Thus, it is extremely useful to know how to solve them numerically through the use of computer programming. This project implements two different numerical methods to solve a 2D time-independent wave equation: Finite Difference Methods (specifically, the Centered Finite Difference Method) and Deep Learning (specifically, a Physics Informed Neural Network).

# Features

**Centered Finite Difference Method:** The PDE is defined over a continuous domain. This method involves discretizing that continuous domain into a grid. The technique then involves deriving a formula for solving the PDE at a given grid point $U_{i,j}$.

**Physics Informed Neural Network (PINN):** PINNs are neural networks with a PDE added to the loss function in order to promote solutions that satisfy known physics. For this project we build a PINN to solve our PDE using tensorflow and keras.

This project integrates PDEs, computer programming, finite difference methods and neural networks to great effect. Furthermore, it showcases one of the wonderful applications of neural networks (PINNs).