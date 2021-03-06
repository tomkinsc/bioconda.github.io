:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-snplocs.hsapiens.dbsnp.20120608'
.. highlight: bash

bioconductor-snplocs.hsapiens.dbsnp.20120608
============================================

.. conda:recipe:: bioconductor-snplocs.hsapiens.dbsnp.20120608
   :replaces_section_title:

   SNP locations and alleles for Homo sapiens extracted from NCBI dbSNP Build 137. The source data files used for this package were created by NCBI on June 7\-8\, 2012\, and contain SNPs mapped to reference genome GRCh37.p5. WARNING\: Note that the GRCh37.p5 genome is a patched version of GRCh37 but the patch doesn\'t alter chromosomes 1\-22\, X\, Y\, MT. GRCh37 itself is the same as the hg19 genome from UCSC \*except\* for the mitochondrion chromosome. Therefore\, the SNPs in this package can be \"injected\" in BSgenome.Hsapiens.UCSC.hg19 and they will land at the correct location but this injection will exclude chrM \(i.e. nothing will be injected in that sequence\). IMPORTANT NOTE\: This package is deprecated. Please use a SNPlocs data package based on a more recent dbSNP BUILD instead \(e.g. BUILD 144 or BUILD 149\). You can call BSgenome\:\:available.SNPs\(\) from R to get the list of available SNPlocs data packages.

   :homepage: https://bioconductor.org/packages/3.8/data/annotation/html/SNPlocs.Hsapiens.dbSNP.20120608.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-snplocs.hsapiens.dbsnp.20120608 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-snplocs.hsapiens.dbsnp.20120608>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-snplocs.hsapiens.dbsnp.20120608/meta.yaml>`_

   


.. conda:package:: bioconductor-snplocs.hsapiens.dbsnp.20120608

   |downloads_bioconductor-snplocs.hsapiens.dbsnp.20120608| |docker_bioconductor-snplocs.hsapiens.dbsnp.20120608|

   :versions: 0.99.11-0
   
   :depends bioconductor-bsgenome: >=1.50.0,<1.51.0
   :depends bioconductor-genomicranges: >=1.34.0,<1.35.0
   :depends bioconductor-iranges: >=2.16.0,<2.17.0
   :depends r-base: >=3.5.1,<3.5.2.0a0
   :depends wget: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-snplocs.hsapiens.dbsnp.20120608

   and update with::

      conda update bioconductor-snplocs.hsapiens.dbsnp.20120608

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-snplocs.hsapiens.dbsnp.20120608:<tag>

   (see `bioconductor-snplocs.hsapiens.dbsnp.20120608/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-snplocs.hsapiens.dbsnp.20120608| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-snplocs.hsapiens.dbsnp.20120608.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-snplocs.hsapiens.dbsnp.20120608| image:: https://quay.io/repository/biocontainers/bioconductor-snplocs.hsapiens.dbsnp.20120608/status
   :target: https://quay.io/repository/biocontainers/bioconductor-snplocs.hsapiens.dbsnp.20120608
.. _`bioconductor-snplocs.hsapiens.dbsnp.20120608/tags`: https://quay.io/repository/biocontainers/bioconductor-snplocs.hsapiens.dbsnp.20120608?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-snplocs.hsapiens.dbsnp.20120608/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-snplocs.hsapiens.dbsnp.20120608/README.html