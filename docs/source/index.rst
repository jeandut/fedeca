FedECA documentation
======================

This package allows to perform both simulations and deployments of federated
external control arms (FedECA) analyses.

Before using this code make sure to: 

#. read and accept the terms of the license license.md that can be found at the root of the repository.
#. read `substra's privacy strategy <https://docs.substra.org/en/stable/additional/privacy-strategy.html>`_
#. read our associated technical article
#. `activate secure rng in Opacus <https://opacus.ai/docs/faq#:~:text=What%20is%20the%20secure_rng,the%20security%20this%20brings.>`_ if you plan on using differential privacy.



Citing this work
----------------

::

   @article{duterrailfedeca2023,
   title={FedECA: A Federated External Control Arm Method for Causal Inference with Time-To-Event Data in Distributed Settings},
   author={Ogier du Terrail, Jean and Klopfenstein, Quentin and Li Honghao and Mayer, Imke and Loiseau, Nicolas and Hallal Mohammad and Balazard, Félix and Andreux, Mathieu},
   year={2023},
   doi = {no.doi.yet},
   journal={arXiv},
   }

License
-------

FedECA is released under a custom license that can be found under license.md at the root of the repository.

.. toctree::
   :maxdepth: 0
   :caption: Installation
   
   installation

.. toctree::
   :maxdepth: 0
   :caption: Getting Started Instructions
   
   quickstart

.. toctree::
   :hidden:
   :maxdepth: 4
   :caption: API

   api/fedeca
   api/competitors
   api/algorithms
   api/metrics
   api/scripts
   api/strategies
   api/utils
