---
layout: page
title: Open Science
permalink: /openscience/
---

Open Science is one of my main conserns in research for two main reasons:
* it allows for technical review and replication of results. Material and methods sections of journal papers can be sometimes too short to explain what is really behind a result. 
* once a result is established, sharing the ressources that led to the conclusion is a good start for learning, teaching or communicating with other scientists.

My research are higly transdiscipinary. With this page, I hope to advertise and sum up my contribution to and for a trully Open Science. All my projects are stored on GitHub, you can acces my public at [this link][github-link]. Here is a non-sxhaustive list of projects further advertised on this webpage:
* [NeuRon Virtulizer or NRV]({% link open_science/NRV.markdown %}): this python package is contains models of electrical interactions (stimulation, recording and impedance measurment) of peripheral nerve. A large part of my research is dedicated on this tools that simulates influence of arbitrary stimuli on axonal activity. NRV code can be found on [this page][nrv-github] ; it is based on other scientifically recordnized third parties software such as [Neuron][nrn-page] and [the FEniCS project][fenics-page], and marginally COMSOL (not required as non-open source, however well used in the modeling community, used for comparative purpose mainly). NRV can be easilly installed using pip (see [NRV's pypi page][nrv-pypi]), a full documentation of the project is [hosted on ReadTheDocs][nrv-readthedocs].
* [BIMMS]({% link open_science/BIMMS.markdown %}): this project is both open hardware and open software for electrical impedance measurements of bio-electronic electrodes. Spectroscopic, galvanostatic or potentiostatic, in 2- or 3- or 4-points configurations are possible. More complex measures with custom stimuli (multisine, random...) is also possible. You can access the code and design files on [this github page][bimms-github] and it is possible to install a Python interface using pip (see [BIMMS's pypi page][bimms-pypi]). This tool has been scientifically validated and published in [Hardware-X][bimms-hardwareX]. 



[github-link]: https://github.com/fkolbl/

[nrv-github]: https://github.com/fkolbl/NRV
[nrv-pypi]: https://pypi.org/project/nrv-py/
[nrv-readthedocs]: https://nrv.readthedocs.io/en/latest/

[nrn-page]: https://www.neuron.yale.edu/neuron/
[fenics-page]: https://fenicsproject.org
[COMSOL-page]: https://www.comsol.com

[bimms-github]: https://github.com/fkolbl/BIMMS
[bimms-pypi]: https://pypi.org/project/bimms/
[bimms-hardwareX]: https://www.hardware-x.com/article/S2468-0672(22)00132-8/fulltext