.. RTD-test documentation master file, created by
   sphinx-quickstart on Thu Oct 21 09:47:36 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

M&P test metadata documentation
====================================

Welcome to our test metadata documentation; blah blah

Catalog Fields
**************

+------------------+-------------------------------------------------------+
| Element          | Definition                                            |
+==================+=======================================================+
| :ref:`_version`  | The current version number for the data collection.   |
+------------------+-------------------------------------------------------+
| Study Title      | The title of the study.                               |
+------------------+-------------------------------------------------------+
| Alternate Titles | The name by which a data collection may be commonly   |
|                  | referred to, or as provided by the PI.                |
+------------------+-------------------------------------------------------+

Usage
*****

.. _version:

Version
-------
.. list-table:: Version
   :widths: 25 25 50
   :header-rows: 1

   * - Heading row 1, column 1
     - Heading row 1, column 2
     - Heading row 1, column 3
   * - Row 1, column 1
     -
     - Row 1, column 3
   * - Row 2, column 1
     - Row 2, column 2
     - Versioning begins when a data collection is first archived. Each subsequent update of the data increments the version number by 1. Changes and additions to the data, to the technical documentation, and to the collection as whole (such as adding setup files) trigger a version change. Metadata patches will not get a version change. The Version field is used as the source of the version identifier for the Citation field. Each version also receives a unique DOI (unversioned DOIs redirect to the current version).



.. toctree::
   :maxdepth: 2
   :caption: Contents:
