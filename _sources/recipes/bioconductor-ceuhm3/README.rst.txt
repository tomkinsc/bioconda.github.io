:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-ceuhm3'
.. highlight: bash

bioconductor-ceuhm3
===================

.. conda:recipe:: bioconductor-ceuhm3
   :replaces_section_title:

   ceuhm3\: genotype \(HapMap phase III\) and expression data for CEPH CEU cohort

   :homepage: https://bioconductor.org/packages/3.8/data/experiment/html/ceuhm3.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-ceuhm3 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ceuhm3>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ceuhm3/meta.yaml>`_

   


.. conda:package:: bioconductor-ceuhm3

   |downloads_bioconductor-ceuhm3| |docker_bioconductor-ceuhm3|

   :versions: 0.20.0-0
   
   :depends bioconductor-biobase: >=2.42.0,<2.43.0
   :depends bioconductor-ggbase: >=3.44.0,<3.45.0
   :depends bioconductor-ggtools: >=5.18.0,<5.19.0
   :depends r-base: >=3.5.1,<3.5.2.0a0
   :depends wget: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-ceuhm3

   and update with::

      conda update bioconductor-ceuhm3

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-ceuhm3:<tag>

   (see `bioconductor-ceuhm3/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-ceuhm3| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-ceuhm3.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-ceuhm3| image:: https://quay.io/repository/biocontainers/bioconductor-ceuhm3/status
   :target: https://quay.io/repository/biocontainers/bioconductor-ceuhm3
.. _`bioconductor-ceuhm3/tags`: https://quay.io/repository/biocontainers/bioconductor-ceuhm3?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-ceuhm3/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-ceuhm3/README.html