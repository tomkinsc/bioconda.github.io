:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-epidish'
.. highlight: bash

bioconductor-epidish
====================

.. conda:recipe:: bioconductor-epidish
   :replaces_section_title:

   EpiDISH is a R package to infer the proportions of a priori known cell subtypes present in a sample representing a mixture of such cell\-types. Inference proceeds via one of 3 methods \(Robust Partial Correlations\-RPC\, Cibersort \(CBS\)\, Constrained Projection \(CP\)\)\, as determined by user.

   :homepage: https://bioconductor.org/packages/3.8/bioc/html/EpiDISH.html
   :license: GPL-2
   :recipe: /`bioconductor-epidish <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-epidish>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-epidish/meta.yaml>`_

   


.. conda:package:: bioconductor-epidish

   |downloads_bioconductor-epidish| |docker_bioconductor-epidish|

   :versions: 1.4.1-0
   
   :depends r-base: >=3.5.1,<3.5.2.0a0
   :depends r-e1071: 
   :depends r-mass: 
   :depends r-quadprog: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-epidish

   and update with::

      conda update bioconductor-epidish

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-epidish:<tag>

   (see `bioconductor-epidish/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-epidish| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-epidish.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-epidish| image:: https://quay.io/repository/biocontainers/bioconductor-epidish/status
   :target: https://quay.io/repository/biocontainers/bioconductor-epidish
.. _`bioconductor-epidish/tags`: https://quay.io/repository/biocontainers/bioconductor-epidish?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-epidish/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-epidish/README.html