.. include:: /Includes.rst.txt
.. _columns-properties-label:

=====
label
=====

.. confval:: label

   :Path: $GLOBALS['TCA'][$table]['columns'][$field]
   :Required: true
   :type: string or LLL reference
   :Scope: Display

   The name of the field as shown in the form:

   .. include:: /Images/Rst/Label.rst.txt

   .. note::
      Labels can be overridden in the
      :ref:`types definition <types-properties-showitem>` and the
      :ref:`palettes definition <palettes-properties-showitem>`.
