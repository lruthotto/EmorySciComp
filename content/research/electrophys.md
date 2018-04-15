---
title: "Data Assimilation and Parameter identification in electrophysiology"
date: 2017-11-21T09:59:16-04:00
draft: false
weight: 7
img: "electrophys.png"
---

Data Assimilation is the ensemble of methods for merging data and numerical simulations when solving a specific problem. It can be pursued in different ways and for addressing different problems, from prediction to parameter identification. In this project, we specifically address the variational estimation of the conductivity parameters of the Bidomain equations. These are partial differential equations for the potential propagation in the cardiac tissue. The conductivity tensor is a critical set pf parameters with a major impact on the numerical solution. Their accurate knowledge is hard to obtain in practice. Moving from measurements of the potential on the surface of the tissue, it is possible to obtain a reliable estimate to be used in more complex problems like the optimal placement of cardiac leads. We pursue a variational approach, i.e. the minimization of the mismatch between data and simulations, constrained by the Bidomain equations or their simplified version, the Mondomain equation. As the computational costs are quite high, we need reduced models to pursue the estimation in short timelines. We work currently with approaches like Proper Orthogonal Decomposition and Proper General Decomposition.


PI: [Alessandro Veneziani](http://www.mathcs.emory.edu/~ale)

Funding: US National Science Foundation award DMS 1412963 

This is joint work with F. Fenton (Dept. of Physics, GA Tech), A. Gizzi (Campus Biomedico, Rome, IT), S. Perotto (Dept. of Mathematics, Politecnico di Milano, IT).  