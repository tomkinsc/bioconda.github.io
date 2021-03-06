:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-mirnatarget'
.. highlight: bash

bioconductor-mirnatarget
========================

.. conda:recipe:: bioconductor-mirnatarget
   :replaces_section_title:

   gene target tabale of miRNA for human\/mouse used for MiRaGE package

   :homepage: https://bioconductor.org/packages/3.8/data/experiment/html/miRNATarget.html
   :license: GPL
   :recipe: /`bioconductor-mirnatarget <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mirnatarget>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mirnatarget/meta.yaml>`_

   


.. conda:package:: bioconductor-mirnatarget

   |downloads_bioconductor-mirnatarget| |docker_bioconductor-mirnatarget|

   :versions: 1.20.0-0
   
   :depends bioconductor-biobase: >=2.42.0,<2.43.0
   :depends r-base: >=3.5.1,<3.5.2.0a0
   :depends wget: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-mirnatarget

   and update with::

      conda update bioconductor-mirnatarget

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-mirnatarget:<tag>

   (see `bioconductor-mirnatarget/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-mirnatarget| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-mirnatarget.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-mirnatarget| image:: https://quay.io/repository/biocontainers/bioconductor-mirnatarget/status
   :target: https://quay.io/repository/biocontainers/bioconductor-mirnatarget
.. _`bioconductor-mirnatarget/tags`: https://quay.io/repository/biocontainers/bioconductor-mirnatarget?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-mirnatarget/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-mirnatarget/README.html