:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-mugaexampledata'
.. highlight: bash

bioconductor-mugaexampledata
============================

.. conda:recipe:: bioconductor-mugaexampledata
   :replaces_section_title:

   This package contains example data for the MUGA array that is used by the R package DOQTL.

   :homepage: https://bioconductor.org/packages/3.8/data/experiment/html/MUGAExampleData.html
   :license: GPL-3
   :recipe: /`bioconductor-mugaexampledata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mugaexampledata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mugaexampledata/meta.yaml>`_

   


.. conda:package:: bioconductor-mugaexampledata

   |downloads_bioconductor-mugaexampledata| |docker_bioconductor-mugaexampledata|

   :versions: 1.2.0-0
   
   :depends r-base: >=3.5.1,<3.5.2.0a0
   :depends wget: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-mugaexampledata

   and update with::

      conda update bioconductor-mugaexampledata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-mugaexampledata:<tag>

   (see `bioconductor-mugaexampledata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-mugaexampledata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-mugaexampledata.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-mugaexampledata| image:: https://quay.io/repository/biocontainers/bioconductor-mugaexampledata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-mugaexampledata
.. _`bioconductor-mugaexampledata/tags`: https://quay.io/repository/biocontainers/bioconductor-mugaexampledata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-mugaexampledata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-mugaexampledata/README.html