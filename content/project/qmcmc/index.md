---
title: Quantum-enhanced Markov chain Monte Carlo optimisation
summary: |+ 
    Developed a hybrid algorithm for optimising parametrized proposal strategies in quantum‑enhanced Monte Carlo Markov chains. A Python simulator of the algorithm is available on my [GitHub](https://github.com/DanieleCucurachi/QMCMC.git). Currently in the process of finalizing and preparing this project for submission to a peer‑reviewed journal.
    {style="text-align: justify;"}

    **Supervisors:** [Prof. Crispin Barnes](https://www.phy.cam.ac.uk/directory/barnesc), [Prof. Giuseppe Carleo](https://people.epfl.ch/giuseppe.carleo?lang=en), [Dr. Hugo V. Lepage](https://www.qi.phy.cam.ac.uk/people/).

    **Colleagues:** [Chris Long](https://www.qi.phy.cam.ac.uk/people/)
tags:
  - Algorithms
  - Quantum Computing
date: '2023-06-02T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: High-level representation of the optimisation algorithm.
  focal_point: Smart

links: []
  # - icon: twitter
  #   icon_pack: fab
  #   name: Follow
  #   url: https://twitter.com/georgecushen

url_code: ''
url_video: ''
url_link: ''

pdf: 
url_pdf: uploads/Master_Thesis.pdf


# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:
url_slides: 
---

The combination of classical Markov chains Monte Carlo (MCMC) methods with quantum computers showed potential for achieving quantum advantage in sampling from complex probability distributions, a computationally hard task arising in many diverse fields. Quantum-enhanced proposal distributions, defined by parameterized unitaries, could outperform classical strategies in proposing effective moves in MCMC. However, it is crucial to carefully tune the values of the parameters defining the quantum proposal distribution, as they determine the resulting advantage over the classical counterpart. A general optimization method becomes essential when considering problems where is not possible to identify a reasonable parameter set. This could happen when adopting complicated proposal strategies depending on a large number of parameters, or simply when no prior or relevant information about the problem is available. In the present work, we propose a general optimization algorithm that exploits estimates of the autocorrelation function of a certain observable, calculated over a set of samples, to optimize the parameters defining the proposal distribution.
{style="text-align: justify;"}

A Python simulator of the algorithm is available on my [GitHub](https://github.com/DanieleCucurachi/QMCMC.git).
