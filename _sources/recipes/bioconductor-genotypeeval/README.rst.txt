:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-genotypeeval'
.. highlight: bash

bioconductor-genotypeeval
=========================

.. conda:recipe:: bioconductor-genotypeeval
   :replaces_section_title:

   Takes in a gVCF or VCF and reports metrics to assess quality of calls.

   :homepage: https://bioconductor.org/packages/3.8/bioc/html/genotypeeval.html
   :license: file LICENSE
   :recipe: /`bioconductor-genotypeeval <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-genotypeeval>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-genotypeeval/meta.yaml>`_

   


.. conda:package:: bioconductor-genotypeeval

   |downloads_bioconductor-genotypeeval| |docker_bioconductor-genotypeeval|

   :versions: 1.14.0-0
   
   :depends bioconductor-biocgenerics: >=0.28.0,<0.29.0
   :depends bioconductor-biocparallel: >=1.16.0,<1.17.0
   :depends bioconductor-genomeinfodb: >=1.18.0,<1.19.0
   :depends bioconductor-genomicranges: >=1.34.0,<1.35.0
   :depends bioconductor-iranges: >=2.16.0,<2.17.0
   :depends bioconductor-rtracklayer: >=1.42.0,<1.43.0
   :depends bioconductor-variantannotation: >=1.28.0,<1.29.0
   :depends r-base: >=3.5.1,<3.5.2.0a0
   :depends r-ggplot2: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-genotypeeval

   and update with::

      conda update bioconductor-genotypeeval

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-genotypeeval:<tag>

   (see `bioconductor-genotypeeval/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-genotypeeval| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-genotypeeval.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-genotypeeval| image:: https://quay.io/repository/biocontainers/bioconductor-genotypeeval/status
   :target: https://quay.io/repository/biocontainers/bioconductor-genotypeeval
.. _`bioconductor-genotypeeval/tags`: https://quay.io/repository/biocontainers/bioconductor-genotypeeval?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-genotypeeval/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-genotypeeval/README.html