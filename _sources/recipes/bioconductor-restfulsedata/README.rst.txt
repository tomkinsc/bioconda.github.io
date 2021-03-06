:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-restfulsedata'
.. highlight: bash

bioconductor-restfulsedata
==========================

.. conda:recipe:: bioconductor-restfulsedata
   :replaces_section_title:

   Metadata RangedSummarizedExperiment shell for use with restfulSE.

   :homepage: https://bioconductor.org/packages/3.8/data/experiment/html/restfulSEData.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-restfulsedata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-restfulsedata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-restfulsedata/meta.yaml>`_

   


.. conda:package:: bioconductor-restfulsedata

   |downloads_bioconductor-restfulsedata| |docker_bioconductor-restfulsedata|

   :versions: 1.4.0-0
   
   :depends bioconductor-experimenthub: >=1.8.0,<1.9.0
   :depends bioconductor-summarizedexperiment: >=1.12.0,<1.13.0
   :depends r-base: >=3.5.1,<3.5.2.0a0
   :depends wget: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-restfulsedata

   and update with::

      conda update bioconductor-restfulsedata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-restfulsedata:<tag>

   (see `bioconductor-restfulsedata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-restfulsedata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-restfulsedata.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-restfulsedata| image:: https://quay.io/repository/biocontainers/bioconductor-restfulsedata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-restfulsedata
.. _`bioconductor-restfulsedata/tags`: https://quay.io/repository/biocontainers/bioconductor-restfulsedata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-restfulsedata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-restfulsedata/README.html