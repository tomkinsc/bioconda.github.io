:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-complexheatmap'
.. highlight: bash

bioconductor-complexheatmap
===========================

.. conda:recipe:: bioconductor-complexheatmap
   :replaces_section_title:

   Complex heatmaps are efficient to visualize associations between different sources of data sets and reveal potential structures. Here the ComplexHeatmap package provides a highly flexible way to arrange multiple heatmaps and supports self\-defined annotation graphics.

   :homepage: https://bioconductor.org/packages/3.8/bioc/html/ComplexHeatmap.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-complexheatmap <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-complexheatmap>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-complexheatmap/meta.yaml>`_
   :links: biotools: :biotools:`complexheatmap`

   


.. conda:package:: bioconductor-complexheatmap

   |downloads_bioconductor-complexheatmap| |docker_bioconductor-complexheatmap|

   :versions: 1.20.0-0, 1.18.1-0, 1.17.1-0, 1.14.0-0, 1.6.0-1, 1.6.0-0
   
   :depends r-base: >=3.5.1,<3.5.2.0a0
   :depends r-circlize: >=0.4.1
   :depends r-colorspace: 
   :depends r-getoptlong: 
   :depends r-globaloptions: >=0.1.0
   :depends r-rcolorbrewer: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-complexheatmap

   and update with::

      conda update bioconductor-complexheatmap

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-complexheatmap:<tag>

   (see `bioconductor-complexheatmap/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-complexheatmap| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-complexheatmap.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-complexheatmap| image:: https://quay.io/repository/biocontainers/bioconductor-complexheatmap/status
   :target: https://quay.io/repository/biocontainers/bioconductor-complexheatmap
.. _`bioconductor-complexheatmap/tags`: https://quay.io/repository/biocontainers/bioconductor-complexheatmap?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-complexheatmap/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-complexheatmap/README.html