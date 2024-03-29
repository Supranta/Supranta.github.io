---
layout: page
title: Research
permalink: /research/
description: Description of my research interests
---

I am interested in different aspects of data-driven observational cosmology.

**Field-level inference for weak lensing data**

Standard methods of cosmological analysis rely on using summary statistics to infer cosmological parameters. However, utilizing information from the full-field is necessary to optimally constrain these parameters. We have developed such a field-level inference code (See [here](https://arxiv.org/pdf/2204.13216.pdf)) that allows us to extract all the available information from a weak lensing catalogue. We [forecast](https://arxiv.org/pdf/2307.00070.pdf) that field-level inference can put 2x stronger constraints on cosmological parameters than usual power spectrum constraints.

As a part of this research program, we have developed KaRMMa, a curved sky forward-modeled mass map reconstruction code (See [here](https://arxiv.org/pdf/2105.14699.pdf) and [here](https://arxiv.org/pdf/2210.12280.pdf)). In one of our recent [work](https://arxiv.org/pdf/2403.05484.pdf), we used KaRMMa to produce Bayesian mass maps with the Dark Energy Survey weak lensing data (See the figure below). 

<img src="{{ site.baseurl }}/assets/img/research/KaRMMa_DES.png" width="700" height="500" alt="" title="karmma"/>

**Generative adversarial networks for fast weak lensing simulations**

We have developed a method for producing fast weak lensing simulations using generative adversarial network (GANs). In our physically motivated method, we input lognormal maps into our GAN which then turns it into a simulation quality map (See [here](https://ui.adsabs.harvard.edu/abs/2022mla..confE...8F/abstract)). This method will drastically reduce the computational requirements for the analysis with next-generation weak lensing surveys like LSST. 

**Machine learning based emulators for fast weak lensing and galaxy clustering analysis**

I have also developed a machine-learning based emulator (see [here](https://arxiv.org/pdf/2203.06124.pdf)) that accelerate 3x2 point cosmological analysis by 1000 times. As a part of the LSST Dark Energy Science Collaboration, we then used this emulator to map out the impact of various systematic effects on 3x2pt analysis with LSST (see [here](https://arxiv.org/pdf/2403.11797.pdf)).

My collaborators have extended the machine learning architectures of this emulator and used it to explore other aspects of 3x2 pt analysis with this emulator (See [here](https://arxiv.org/pdf/2402.17716.pdf) and [here](https://arxiv.org/pdf/2403.12337.pdf)).  

**Peculiar Velocity analysis in the local Universe:**

During my PhD, I studied the peculiar velocity field of the local Universe. This is important for two reasons: i) We can infer the growth rate of structure ($$f\sigma_8$$) from these observations. ii) Peculiar velocities are a source of systematic errors in the measurement of the expansion rate ($$H_0$$).

In [one of our papers](https://arxiv.org/pdf/1912.09383.pdf), we obtained constraints on $$f\sigma_8$$ which is competitive with other probes of structure growth (See the figure below).

<img src="{{ site.baseurl }}/assets/img/research/fsigma8.png" width="700" height="400" alt="" title="fs8"/>

In [another paper](https://arxiv.org/pdf/2010.01119.pdf), we investigated the role peculiar velocity errors plays in the inference of $$H_0$$.

**Theoretical early Universe cosmology:**

Previously, I have also worked on theoretical aspects of early universe cosmology. We [studied a modification to gravity called Cuscuton in the early universe](https://arxiv.org/abs/1704.01131) and proposed an [alternative to Inflation](https://arxiv.org/abs/1802.06818) based on it.
