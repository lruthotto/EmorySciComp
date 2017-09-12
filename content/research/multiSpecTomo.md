---
title: "Numerical Methods for Multispectral Tomographic Image Reconstruction"
date: 2017-09-10T09:59:16-04:00
draft: false
---

Breast cancer is the most prevalent non-skin cancer in women in the
US.  Although mammography is currently the most common test for the
early detection and diagnosis of breast cancer, its two-dimensional
nature introduces various limitations in its capabilities for advanced
imaging. Over the last decade, the introduction of digital imaging
technology has resulted in the development of new tomographic and
pseudo-tomographic methods for imaging the breast.

Digital tomographic image reconstruction uses multiple x-ray
projections obtained along a range of different incident angles to
reconstruct a 3D representation of an object. For example, computed
tomography (CT) generally refers to the situation when a full set of
angles are used (e.g., 360 degrees) while tomosynthesis refers to the
case when only a limited (e.g., 30 degrees) angular range is used. In
either case, most existing reconstruction algorithms assume that the
x-ray source is monoenergetic. This results in a simplified linear
forward model, which is easy to solve but can result in artifacts in
the reconstructed images. It has been shown that these artifacts can
be reduced by using a more accurate polyenergetic assumption for the
x-ray source, but the polyenergetic model requires solving a
large-scale nonlinear inverse problem.  In addition to reducing
artifacts, a full polyenergetic model can be used to extract
additional information about the materials of the object; that is, to
provide a mechanism for quantitative imaging.  Similar mathematical
models arise when using multispectral detectors.

The aim of this project is to develop algorithms and software to
solve these very challenging inverse problems.

PI: [James Nagy](http://www.mathcs.emory.edu/~nagy)

This is joint work with Martin Andersen, Technical University of Denmark,
and Ioannis Sechopoulos, Radboud University Medical Center, and is paritally
funded by a grant from the US National Institute of Health.
