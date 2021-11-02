###########
PART 1--testing
###########

.. _testlink:

Just some text... I wish I could link to this!

******
Ch. 2
******

Section test
=============

Just some **bold** text. Jump to :ref:`mylist`

Subsection test
---------------

just some *italicized* text

Subsubsection
^^^^^^^^^^^^^

.. _mylist:
* List test
* And another item

    * nested!
    * nested again

*and back out

and now a little table...

.. csv-table:: Test1
   :file: "./test-table.csv"
   :widths: 30, 70

blah
Bibliographic


blah

And now let's go to the top :ref:`testlink`

Or we could try to go to :ref:`Ch. 2`

And finally, I will try to go to :doc:`index-old`
