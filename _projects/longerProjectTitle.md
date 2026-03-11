---
layout: post
title: HCP-EP Functional Dysconnectivity
description: Using rs-fMRI to assess connectivity differences between people with early-psychosis and healthy controls.
---

Under the supervison of Dr. Katie Lavigne, I completed a one-year research project employing Multivariate Distance Matrix Regression (MDMR) to investigate functional connectivity differences between early-psychosis patients and healthy controls. We used resting state functional MRI and cognitive data from the Human Connectome Project for Early Psychosis, an open (but access-controlled) dataset. 

Background
============

Connectivity changes in patients with early psychosis, broadly defined as within five (5) years of psychosis symptoms, has been studied using the Regions of Interest (ROI) approach which narrows the scope of investigation and limits our understanding of how the brain functions as a whole that may have impacted cognition. Additionally, analysis models typically impose a normality assumption of the underlying distribution of data, which, in a multivariate case, is impractical. Thus, we investigated how functional connectivity elucidated by resting-state functional MRI differs between early-psychosis patients and healthy controls in relation to cognition.

Multivariate Distance Matrix Regression (MDMR) offers a non-parametric alternative to multivariate linear regression and has been employed to Connectome Wide Association Studies (see [Shezad et al., 2014](https://doi.org/10.1016/j.neuroimage.2014.02.024) and [Misaki et al., 2018](https://doi.org/10.1016/j.nicl.2018.08.025)). The mathematics behind MDMR is described in [Zapala, & Schork (2012)](https://doi.org/10.3389/fgene.2012.00190) and [McArtor, Lubke, & Bergeman (2017)](https://doi.org/10.1007/s11336-016-9527-8).

Code
============
If you're intersted in using MDMR, I have shared the code I used for my project [here](https://github.com/fancatfkl/HCP-EP-functional-dysconnectivity).

