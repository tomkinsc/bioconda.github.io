:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-cancersubtypes'
.. highlight: bash

bioconductor-cancersubtypes
===========================

.. conda:recipe:: bioconductor-cancersubtypes
   :replaces_section_title:

   CancerSubtypes integrates the current common computational biology methods for cancer subtypes identification and provides a standardized framework for cancer subtype analysis based multi\-omics data\, such as gene expression\, miRNA expression\, DNA methylation and others.

   :homepage: https://bioconductor.org/packages/3.8/bioc/html/CancerSubtypes.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-cancersubtypes <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cancersubtypes>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cancersubtypes/meta.yaml>`_
   :links: biotools: :biotools:`cancersubtypes`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-cancersubtypes

   |downloads_bioconductor-cancersubtypes| |docker_bioconductor-cancersubtypes|

   :versions: 1.8.0-0, 1.6.0-0, 1.4.0-0
   
   :depends bioconductor-consensusclusterplus: >=1.46.0,<1.47.0
   :depends bioconductor-impute: >=1.56.0,<1.57.0
   :depends bioconductor-limma: >=3.38.0,<3.39.0
   :depends r-base: >=3.5.1,<3.5.2.0a0
   :depends r-cluster: 
   :depends r-icluster: 
   :depends r-nmf: 
   :depends r-sigclust: 
   :depends r-snftool: 
   :depends r-survival: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-cancersubtypes

   and update with::

      conda update bioconductor-cancersubtypes

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-cancersubtypes:<tag>

   (see `bioconductor-cancersubtypes/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-cancersubtypes| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-cancersubtypes.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-cancersubtypes| image:: https://quay.io/repository/biocontainers/bioconductor-cancersubtypes/status
   :target: https://quay.io/repository/biocontainers/bioconductor-cancersubtypes
.. _`bioconductor-cancersubtypes/tags`: https://quay.io/repository/biocontainers/bioconductor-cancersubtypes?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-cancersubtypes/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-cancersubtypes/README.html