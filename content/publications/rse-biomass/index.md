---
author: Ethan Emick, Chad Babcock, Grayson W. White, Andrew T. Hudak, Grant M. Domke, and Andrew O. Finley
date: "2023-06-22"
draft: false
excerpt: Remote Sensing of Environment.
layout: single
title: >
  An approach to estimating forest biomass while quantifying estimate uncertainty and correcting bias in machine learning maps
---

### Abstract

Providing forest biomass estimates with desired accuracy and precision for small areas is a key challenge to
incorporating forest carbon offsets into commodity trading programs. Enrolled forest carbon projects and 
verification entities typically rely on probabilistically sampled field data and design-based (DB) estimators to 
estimate carbon storage and characterize uncertainty. However, this methodology requires a large amount of field
data to achieve sufficient precision and collection of these data can be prohibitively expensive. This has spurred
interest in developing regional-scale maps of forest biomass that incorporate remote sensing data as an 
alternative to collecting expensive plot data. These maps are often generated using machine learning (ML) algorithms
that combine remote sensing products and field measurements. While these maps can produce estimates across
large geographic regions at fine spatial resolutions, the estimates are prone to bias and do not have associated
uncertainty estimates. Here, we assess one such map developed by the National Aeronautics and Space 
Administration’s Carbon Monitoring System. We consider model-assisted (MA) and geostatistical model-based
(GMB) estimators to address map bias and uncertainty quantification. The MA and GMB estimators use a sample
of field observations as the response, and the ML-produced map as an auxiliary variable to achieve statistically
defensible predictions. We compare MA and GMB estimator performance to DB and direct (DR) estimators.
This assessment considers both counties and a small areal extent experimental forest, all within
Oregon USA. Results suggest the MA and GMB estimators perform similar to the DB estimator at the state level
and in counties containing many field plots. But in counties with moderate to small field sample sizes, the GMB
and MA estimators are more precise than the DB estimator. As within-county sample sizes get smaller, the GMB
estimator tends to outperform MA. Results also show the DR estimator’s state-level estimates are substantially
larger than the DB, MA and GMB estimates, indicating that that the DR estimator may be biased. When assessing
the GMB estimator for the experimental forest, we find the GMB estimator has sufficient precision for stand-level
carbon accounting even when no field observations are available within the stand. Plot-level GMB uncertainty
interval coverage probabilities were estimated and showed adequate coverage. This suggests that the GMB
estimator is producing statistically rigorous uncertainty estimates.

### Access

This publication can be found [here](https://www.sciencedirect.com/science/article/pii/S0034425723002298).

