---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'i-PI 2.0: A universal force engine for advanced molecular simulations'
subtitle: ''
summary: ''
authors:
- Venkat Kapil
- Mariana Rossi
- Ondrej Marsalek
- Riccardo Petraglia
- Yair Litman
- Thomas Spura
- Bingqing Cheng
- Alice Cuzzocrea
- Robert H. Meißner
- David M. Wilkins
- Benjamin A. Helfrecht
- Przemysław Juda
- Sébastien P. Bienvenue
- Wei Fang
- Jan Kessler
- Igor Poltavsky
- Steven Vandenbrande
- Jelle Wieme
- Clemence Corminboeuf
- Thomas D. Kühne
- David E. Manolopoulos
- Thomas E. Markland
- Jeremy O. Richardson
- Alexandre Tkatchenko
- Gareth A. Tribello
- Veronique Van Speybroeck
- Michele Ceriotti
tags:
- Accelerated sampling
- Geometry optimizers
- Molecular dynamics
- Path integral
categories: []
date: '2019-03-01'
lastmod: 2023-02-11T13:27:24Z
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2023-02-11T13:27:24.383443Z'
publication_types:
- '2'
abstract: 'Progress in the atomic-scale modeling of matter over the past decade has
  been tremendous. This progress has been brought about by improvements in methods
  for evaluating interatomic forces that work by either solving the electronic structure
  problem explicitly, or by computing accurate approximations of the solution and
  by the development of techniques that use the Born–Oppenheimer (BO) forces to move
  the atoms on the BO potential energy surface. As a consequence of these developments
  it is now possible to identify stable or metastable states, to sample configurations
  consistent with the appropriate thermodynamic ensemble, and to estimate the kinetics
  of reactions and phase transitions. All too often, however, progress is slowed down
  by the bottleneck associated with implementing new optimization algorithms and/or
  sampling techniques into the many existing electronic-structure and empirical-potential
  codes. To address this problem, we are thus releasing a new version of the i-PI
  software. This piece of software is an easily extensible framework for implementing
  advanced atomistic simulation techniques using interatomic potentials and forces
  calculated by an external driver code. While the original version of the code (Ceriotti
  et al., 2014) was developed with a focus on path integral molecular dynamics techniques,
  this second release of i-PI not only includes several new advanced path integral
  methods, but also offers other classes of algorithms. In other words, i-PI is moving
  towards becoming a universal force engine that is both modular and tightly coupled
  to the driver codes that evaluate the potential energy surface and its derivatives.
  Program summary Program Title: i-PI Program Files doi: http://dx.doi.org/10.17632/x792grbm9g.1
  Licensing provisions: GPLv3, MIT Programming language: Python External routines/libraries:
  NumPy Nature of problem: Lowering the implementation barrier to bring state-of-the-art
  sampling and atomistic modeling techniques to ab initio and empirical potentials
  programs. Solution method: Advanced sampling methods, including path-integral molecular
  dynamics techniques, are implemented in a Python interface. Any electronic structure
  code can be patched to receive the atomic coordinates from the Python interface,
  and to return the forces and energy that are used to integrate the equations of
  motion, optimize atomic geometries, etc. Restrictions: This code does not compute
  interatomic potentials, although the distribution includes sample driver codes that
  can be used to test different techniques using a few simple model force fields.'
publication: '*Computer Physics Communications*'
doi: 10.1016/j.cpc.2018.09.020
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0010465518303436
---
