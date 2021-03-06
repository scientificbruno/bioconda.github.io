.. _`prophyle`:

prophyle
========

|downloads|

ProPhyle is a metagenomic classifier based on BWT-index and phylogenetic trees. Its indexing strategy uses bottom-up propagation of k-mers in the tree, assembling contigs at each node and matching using a standard full-text search.

======== ===========
Home     https://github.com/karel-brinda/prophyle
Versions 0.1.0.29, 0.1.0.35, 0.1.0.38
License  MIT
Recipe   https://github.com/bioconda/bioconda-recipes/tree/master/recipes/prophyle
======== ===========

Installation
------------

.. highlight: bash

With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

   conda install prophyle

and update with::

   conda update prophyle



|docker|

A Docker container is available at https://quay.io/repository/biocontainers/prophyle.

Link to this page
-----------------

Render an |badge| badge with the following Markdown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat-square)](http://bioconda.github.io/recipes/prophyle/README.html)

.. |badge| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat-square
           :target: http://bioconda.github.io/recipes/prophyle/README.html
.. |downloads| image:: https://anaconda.org/bioconda/prophyle/badges/downloads.svg
               :target: https://anaconda.org/bioconda/prophyle
.. |docker| image:: https://quay.io/repository/biocontainers/prophyle/status
                :target: https://quay.io/repository/biocontainers/prophyle


