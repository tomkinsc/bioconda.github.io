:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-raggedexperiment'
.. highlight: bash

bioconductor-raggedexperiment
=============================

.. conda:recipe:: bioconductor-raggedexperiment
   :replaces_section_title:

   This package provides a flexible representation of copy number\, mutation\, and other data that fit into the ragged array schema for genomic location data. The basic representation of such data provides a rectangular flat table interface to the user with range information in the rows and samples\/specimen in the columns.

   :homepage: https://bioconductor.org/packages/3.8/bioc/html/RaggedExperiment.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-raggedexperiment <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-raggedexperiment>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-raggedexperiment/meta.yaml>`_

   


.. conda:package:: bioconductor-raggedexperiment

   |downloads_bioconductor-raggedexperiment| |docker_bioconductor-raggedexperiment|

   :versions: 1.6.0-0, 1.4.0-0, 1.2.0-0
   
   :depends bioconductor-biocgenerics: >=0.28.0,<0.29.0
   :depends bioconductor-genomeinfodb: >=1.18.0,<1.19.0
   :depends bioconductor-genomicranges: >=1.34.0,<1.35.0
   :depends bioconductor-iranges: >=2.16.0,<2.17.0
   :depends bioconductor-s4vectors: >=0.20.0,<0.21.0
   :depends bioconductor-summarizedexperiment: >=1.12.0,<1.13.0
   :depends r-base: >=3.5.1,<3.5.2.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-raggedexperiment

   and update with::

      conda update bioconductor-raggedexperiment

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-raggedexperiment:<tag>

   (see `bioconductor-raggedexperiment/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-raggedexperiment| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-raggedexperiment.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-raggedexperiment| image:: https://quay.io/repository/biocontainers/bioconductor-raggedexperiment/status
   :target: https://quay.io/repository/biocontainers/bioconductor-raggedexperiment
.. _`bioconductor-raggedexperiment/tags`: https://quay.io/repository/biocontainers/bioconductor-raggedexperiment?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-raggedexperiment/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-raggedexperiment/README.html