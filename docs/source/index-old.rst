#####################
Part 2 - More Testing
#####################

Welcome to our test metadata documentation; blah blah.

Catalog Fields
**************

+------------------+-------------------------------------------------------+
| Element          | Definition                                            |
+==================+=======================================================+
| :ref:`Version`   | The current version number for the data collection.   |
+------------------+-------------------------------------------------------+
| Study Title      | The title of the study.                               |
+------------------+-------------------------------------------------------+
| Alternate Titles | The name by which a data collection may be commonly   |
|                  | referred to, or as provided by the PI.                |
+------------------+-------------------------------------------------------+

Element

Version
*******
.. csv-table:: Test1
   :file: test-table.csv
   :widths: 30, 70


.. list-table:: Version_field

   * - Description
     - The current version number for the data collection.
   * - Repeatable?
     - No
   * - Required?
     - Yes
   * - Accepted values
     - Numeric
   * - Usage Notes
     - Versioning begins when a data collection is first archived. Each subsequent update of the data increments the version number by 1. Changes and additions to the data, to the technical documentation, and to the collection as whole (such as adding setup files) trigger a version change. Metadata patches will not get a version change. The Version field is used as the source of the version identifier for the Citation field. Each version also receives a unique DOI (unversioned DOIs redirect to the current version).
   * - example
     - 1
