:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-bnbc'
.. highlight: bash

bioconductor-bnbc
=================

.. conda:recipe:: bioconductor-bnbc
   :replaces_section_title:

   Tools to normalize \(several\) Hi\-C data from replicates.

   :homepage: https://bioconductor.org/packages/3.8/bioc/html/bnbc.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-bnbc <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bnbc>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bnbc/meta.yaml>`_

   


.. conda:package:: bioconductor-bnbc

   |downloads_bioconductor-bnbc| |docker_bioconductor-bnbc|

   :versions: 1.4.0-0
   
   :depends bioconductor-biocgenerics: >=0.28.0,<0.29.0
   :depends bioconductor-ebimage: >=4.24.0,<4.25.0
   :depends bioconductor-genomeinfodb: >=1.18.0,<1.19.0
   :depends bioconductor-genomicranges: >=1.34.0,<1.35.0
   :depends bioconductor-iranges: >=2.16.0,<2.17.0
   :depends bioconductor-preprocesscore: >=1.44.0,<1.45.0
   :depends bioconductor-s4vectors: >=0.20.0,<0.21.0
   :depends bioconductor-summarizedexperiment: >=1.12.0,<1.13.0
   :depends bioconductor-sva: >=3.30.0,<3.31.0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-base: >=3.5.1,<3.5.2.0a0
   :depends r-matrixstats: 
   :depends r-rcpp: >=0.12.12
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-bnbc

   and update with::

      conda update bioconductor-bnbc

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-bnbc:<tag>

   (see `bioconductor-bnbc/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-bnbc| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-bnbc.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-bnbc| image:: https://quay.io/repository/biocontainers/bioconductor-bnbc/status
   :target: https://quay.io/repository/biocontainers/bioconductor-bnbc
.. _`bioconductor-bnbc/tags`: https://quay.io/repository/biocontainers/bioconductor-bnbc?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-bnbc/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-bnbc/README.html