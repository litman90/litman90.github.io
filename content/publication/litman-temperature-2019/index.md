---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Temperature dependence of the vibrational spectrum of porphycene: a qualitative
  failure of classical-nuclei molecular dynamics'
subtitle: ''
summary: ''
authors:
- Yair Litman
- Jörg Behler
- Mariana Rossi
tags:
- Yair
categories: []
date: '2019-12-01'
lastmod: 2023-02-11T13:27:23Z
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
publishDate: '2023-02-11T13:27:23.235129Z'
publication_types:
- '2'
abstract: The temperature dependence of vibrational spectra can provide information
  about structural changes of a system and also serve as a probe to identify different
  vibrational mode couplings. Fully anharmonic temperature-dependent calculations
  of these quantities are challenging due to the cost associated with statistically
  converging trajectory-based methods, especially when accounting for nuclear quantum
  effects. Here, we train a high-dimensional neural network potential energy surface
  for the porphycene molecule based on data generated with DFT-B3LYP, including pairwise
  van der Waals interactions. In addition, we fit a kernel ridge regression model
  for the molecular dipole moment surface. The combination of this machinery with
  thermostatted path integral molecular dynamics (TRPMD) allows us to obtain well-converged,
  full-dimensional, fully-anharmonic vibrational spectra including nuclear quantum
  effects, without sacrificing the first-principles quality of the potential-energy
  surface or the dipole surface. Within this framework, we investigate the temperature
  and isotopologue dependence of the high-frequency vibrational fingerprints of porphycene.
  While classical-nuclei dynamics predicts a red shift of the vibrations encompassing
  the NH and CH stretches, TRPMD predicts a strong blue shift in the NH-stretch region
  and a smaller one in the CH-stretch region. We explain this behavior by analyzing
  the modulation of the effective potential with temperature, which arises from vibrational
  coupling between quasi-classical thermally activated modes and high-frequency quantized
  modes.
publication: '*Faraday Discuss.*'
doi: 10.1039/C9FD00056A
links:
- name: URL
  url: https://pubs.rsc.org/en/content/articlelanding/2020/fd/c9fd00056a
---
