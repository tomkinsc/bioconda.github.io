:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'pourrna'
.. highlight: bash

pourrna
=======

.. conda:recipe:: pourRNA
   :replaces_section_title:

   Compute local minima and respective transition rates of an RNA energy landscape.

   :homepage: https://github.com/ViennaRNA/pourRNA/
   :license: GPLv2
   :recipe: /`pourRNA <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/pourRNA>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/pourRNA/meta.yaml>`_

   


.. conda:package:: pourrna

   |downloads_pourrna| |docker_pourrna|

   :versions: 1.1.0-0, 1.0.1-0
   
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends viennarna: >=2.4.11,<2.5.0a0
   :depends viennarna: >=2.4.11,<3.0.0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install pourrna

   and update with::

      conda update pourrna

   or use the docker container::

      docker pull quay.io/biocontainers/pourrna:<tag>

   (see `pourrna/tags`_ for valid values for ``<tag>``)


.. |downloads_pourrna| image:: https://img.shields.io/conda/dn/bioconda/pourrna.svg?style=flat
   :alt:   (downloads)
.. |docker_pourrna| image:: https://quay.io/repository/biocontainers/pourrna/status
   :target: https://quay.io/repository/biocontainers/pourrna
.. _`pourrna/tags`: https://quay.io/repository/biocontainers/pourrna?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/pourrna/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/pourrna/README.html