:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-annotationhubdata'
.. highlight: bash

bioconductor-annotationhubdata
==============================

.. conda:recipe:: bioconductor-annotationhubdata
   :replaces_section_title:

   These recipes convert a wide variety and a growing number of public bioinformatic data sets into easily\-used standard Bioconductor data structures.

   :homepage: https://bioconductor.org/packages/3.8/bioc/html/AnnotationHubData.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-annotationhubdata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-annotationhubdata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-annotationhubdata/meta.yaml>`_
   :links: biotools: :biotools:`annotationhubdata`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-annotationhubdata

   |downloads_bioconductor-annotationhubdata| |docker_bioconductor-annotationhubdata|

   :versions: 1.12.0-0, 1.10.3-0, 1.8.0-0
   
   :depends bioconductor-annotationdbi: >=1.44.0,<1.45.0
   :depends bioconductor-annotationforge: >=1.24.0,<1.25.0
   :depends bioconductor-annotationhub: >=2.14.0,<2.15.0
   :depends bioconductor-biobase: >=2.42.0,<2.43.0
   :depends bioconductor-biocgenerics: >=0.28.0,<0.29.0
   :depends bioconductor-biocviews: >=1.50.0,<1.51.0
   :depends bioconductor-biostrings: >=2.50.0,<2.51.0
   :depends bioconductor-genomeinfodb: >=1.18.0,<1.19.0
   :depends bioconductor-genomicfeatures: >=1.34.0,<1.35.0
   :depends bioconductor-genomicranges: >=1.34.0,<1.35.0
   :depends bioconductor-iranges: >=2.16.0,<2.17.0
   :depends bioconductor-organismdbi: >=1.24.0,<1.25.0
   :depends bioconductor-rbiopaxparser: >=2.22.0,<2.23.0
   :depends bioconductor-rsamtools: >=1.34.0,<1.35.0
   :depends bioconductor-rtracklayer: >=1.42.0,<1.43.0
   :depends bioconductor-s4vectors: >=0.20.0,<0.21.0
   :depends r-base: >=3.5.1,<3.5.2.0a0
   :depends r-biocmanager: 
   :depends r-dbi: 
   :depends r-futile.logger: >=1.3.0
   :depends r-jsonlite: 
   :depends r-rcurl: 
   :depends r-rsqlite: 
   :depends r-xml: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-annotationhubdata

   and update with::

      conda update bioconductor-annotationhubdata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-annotationhubdata:<tag>

   (see `bioconductor-annotationhubdata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-annotationhubdata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-annotationhubdata.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-annotationhubdata| image:: https://quay.io/repository/biocontainers/bioconductor-annotationhubdata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-annotationhubdata
.. _`bioconductor-annotationhubdata/tags`: https://quay.io/repository/biocontainers/bioconductor-annotationhubdata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-annotationhubdata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-annotationhubdata/README.html