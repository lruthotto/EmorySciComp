---
title: "Novel methods for computational hemodynamics"
date: 2017-11-21T09:59:16-04:00
draft: false
weight: 2
img: "comphemo.png"
---

The incompressible Navier-Stokes equations are the basic mathematical model for the simulation of blood flow in arteries. Even if well-known and investigated since a long time, these equations still represent a numerical challenge for their saddle-point structure, the non linear nature. In medical applications, efficiency is a priority together with reliability. All these aspects require the set up of appropriate preconditioners, specific solution methods and, more in general, approaches that could take advantage from particular features of the problem at hand. In addition, we should consider (i) the presence of possible turbulent dynamics and their appropriate numerical modeling; (ii) the lack of data that systematically affects the clinical scenarios (defective problems, image legacy problem). The former is currently solved by Large Eddie Simulation (LES) approaches, specifically based on deconvolution filters. The latter calls for specific methods for the identification of the (arbitrary) missing conditions with low impact on the final solutions. Also, the presence of numerical instabilities induced by backflows is a critical issues in computational hemodynamics. Among the possible solution methods, we also include the Hierarchical Model Reduction technique, a numerical approach for incompressible flow in pipes, where finite elements or isogeometric analysis for the axial direction of the pipe are coupled with spectral methods for a rapid simulation of the transversal dynamics.


PI: [Alessandro Veneziani](http://www.mathcs.emory.edu/~ale)

Funding: US National Science Foundation awards DMS 1419060 and DMS 1620406   

This is joint work with Simona Perotto (Dept. Mathematics, Politecnico di Milano, Italy), Pablo Blanco (LNCC, Petropolis, Brazil), Annalisa Quaini (Dept. of Mathematics, University of Houston, TX), Leo Rebholz (Dept. of Mathematics, Clemson University, SC).