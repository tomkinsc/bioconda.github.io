:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-eupathdb'
.. highlight: bash

bioconductor-eupathdb
=====================

.. conda:recipe:: bioconductor-eupathdb
   :replaces_section_title:

   Brings together annotation resources from the various EuPathDB databases \(PlasmoDB\, ToxoDB\, TriTrypDB\, etc.\) and makes them available in R using the AnnotationHub framework.

   :homepage: https://bioconductor.org/packages/3.8/data/annotation/html/EuPathDB.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-eupathdb <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-eupathdb>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-eupathdb/meta.yaml>`_

   


.. conda:package:: bioconductor-eupathdb

   |downloads_bioconductor-eupathdb| |docker_bioconductor-eupathdb|

   :versions: 1.0.1-0
   
   :depends bioconductor-annotationhub: >=2.14.0,<2.15.0
   :depends bioconductor-annotationhubdata: >=1.12.0,<1.13.0
   :depends bioconductor-biobase: >=2.42.0,<2.43.0
   :depends bioconductor-biostrings: >=2.50.0,<2.51.0
   :depends bioconductor-genomeinfodbdata: >=1.2.0,<1.3.0
   :depends bioconductor-genomicranges: >=1.34.0,<1.35.0
   :depends r-base: >=3.5.1,<3.5.2.0a0
   :depends r-biocmanager: 
   :depends wget: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-eupathdb

   and update with::

      conda update bioconductor-eupathdb

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-eupathdb:<tag>

   (see `bioconductor-eupathdb/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-eupathdb| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-eupathdb.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-eupathdb| image:: https://quay.io/repository/biocontainers/bioconductor-eupathdb/status
   :target: https://quay.io/repository/biocontainers/bioconductor-eupathdb
.. _`bioconductor-eupathdb/tags`: https://quay.io/repository/biocontainers/bioconductor-eupathdb?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-eupathdb/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-eupathdb/README.html