---
layout: page
title: NeuRon Virtualizer (NRV)
permalink: /openscience/nrv/
---

NRV (or NeuRon Virtualizer) is a pythonic framework to enable fast and user friendly simulations of the Peripheral Nervous System. Axons models are simulated with the NEURON software, and extracellular fields are computed either from analytic equations such as point source approximation or with a more detailed description of the nerve and electrode geometry and Finite Elements Method, either using COMSOL (additional commercial licence requiered) or the FENICS project. All computations are performed with the quasistatic approximation of the Maxwell equations, no ephaptic coupling. Stimulation waveform can be of random shapes, and any kinds of electrode can be combined to model complex stimulation strategies.

NRV has been optimized for large population of axons, from generating correct population following a specific diameter repartition, through automatic placement to computation and post-processing of the axons activity when a stimulus is applied. Parallel computation, interface with NEURON and COMSOL and FENICS is automatically handled by NRV. As depicted here below, it accepts various inputs describing the context (stimulation waveform, electrode geometry and nerve geometry and physiological properties), and returns the resulting neural activity (extracellular or membrane recordings, recrutement plots and curves). Automatized optimization of some parameters (stimulus, electrode geometry or even nerve properties) can be performed.

![NRV pipeline](../../assets/images/NRV.png)

NRV has been developped by contributors from the CELL research group at the Laboratory ETIS (UMR CNRS 8051), ENSEA - CY Cergy Paris University, until june 2023 and is now developped and maintained by the Bioelectronics group of laboratory IMS (UMR CNRS 5218), INP Bordeaux, U. Bordeaux.

NRV is intensivelly developped, and a scientific paper is beeing submitted. You can find:
* code repository on [this github page][nrv-github],
* pypi repository page at [this page][nrv-pypi],
* official documentation on [ReadTheDocs][nrv-readthedocs]
A YouTube channel with 
guided video tour is also under reflexion.

[nrv-github]: https://github.com/fkolbl/NRV
[nrv-pypi]: https://pypi.org/project/nrv-py/
[nrv-readthedocs]: https://nrv.readthedocs.io/en/latest/