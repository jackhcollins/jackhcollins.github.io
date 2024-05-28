---
layout: distill
title: Thermodynamics of a VAE
date: 2024-05-27
description: Here is a description of the post
tags: VAE, thermodynamics
categories: Interpretability

bibliography: 2018-12-22-distill.bib

toc:
  -name: Introduction
  -name: Next section
---

## Introduction

The equipartition theorem in Thermodynamics plays a central role in determining and understanding the behaviour of complex systems in thermodynamic equilibrium, linking bulk material properties with the detailed mechanics of the constituent parts. The role that it plays in determining the heat capacity of molecular gases played a central role in the fall of Classical physics and rise of Quantum physics in the late 19th and early 20th Century. The equiparition theorem basically states that the internal energy of a system in thermodynamic equilibrium is equally divided between its independent dynamical degrees of freedom, each degree of freedom getting $$T/2$$ of energy, with the consequence that the heat capacity of a material basically amounts to counting the number of degrees of freedom. Classically, the heat capacity of a simple material like a diatomic gas of $$H_2$$ could therefore be calculated as:

$$C = 7/2$$

This follows from counting 7 degrees of freedom: 3 translational, 2 rotational, 2 vibrational. For a monatomic gas such as Helium, the result would be $C=3/2$ from three translational degrees of freedom.

<div class="row mt-3">
    <div class="col-md-12 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/img2610.gif" class="img-fluid" zoomable=true %}
    </div>
</div>

---

## Next Section

<!--
There are deep connections between Thermodynamics and Variational Inference that in principle are quite well understood, but there are facets of the connection that haven't been properly explored. For me, one of the most fascinating aspects of introductory thermodynamics is the equipartition theorem and its relation to heat capacity. Consider a simple molecular gas like $H_2$. You can think of each $H_2$ molecule as a pair of hydrogen atoms connected by a simple spring that oscillates about some equilibrium displacement, and the gas as a large collection of $H_2$ molecules that are constantly colliding with eachother. Each collision between a pair of molecules will result in some changes in their individual velocities and oscillation rates, but with overall energy being conserved then the net effect of many of these collisions is a randomization of the energy distribution between the various dynamical degrees of freedom. If you were to initialize the system such that all $H_2$ molecules were moving about but their springs were not vibrating and then waited for a while, evntually you would find that much of that kinetic energy has been redistributied into vibrational energy inside the molecules. The equipartition theorem is essentially a formalization of this intuition: for a system in thermodynamic equilibrium\footnote{test}, the total energy budget of the system will be distributed equally between all of the dynamical degrees of freedom.

There is also the Thermodynamic concept of temperature $T$, the high school concept of which is something like "the average speed of a particle in the material", but a better concept is "the average internal energy associated with each degree of freedom". The heat capacity $C$ is the rate of change of internal energy with temperature\footnote{I am making some simplifications here.}:

$$C = \frac{dH}{dT}$$

with $H$ the internal energy. A system with more degrees of freedom has a higher heat capacity. E.g. if you double the number of $H_2% molecules in the case, then you will need twice as much energy to raise the temperature by the same amount. If you replace $H_2$ with a more complex molecular structure with many more internal degrees of freedom, then this also raises the heat capacity because the internal energy is being shared between more degrees of freedom. Specifically, the equipartition

In physics, systems in thermal equilibrium are characterized by their free energy being at a minumum. -->
