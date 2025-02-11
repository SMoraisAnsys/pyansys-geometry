.. _ref_faq:

Frequently asked questions
==========================

What is PyAnsys?
----------------
PyAnsys is a set of open source Python libraries that allow you to interface
with Ansys Electronics Desktop (AEDT), Ansys Mechanical, Ansys Parametric
Design Language (APDL), Ansys Fluent, and other Ansys products.

You can use PyAnsys libraries within a Python environment of your choice
in conjunction with external Python libraries.

What Ansys license is needed to run the Geometry service?
---------------------------------------------------------

.. note::

   This question is answered in https://github.com/ansys/pyansys-geometry/discussions/754.

The Ansys Geometry service is a headless service developed on top of the
modeling libraries for Discovery and SpaceClaim.

Both in its standalone and Docker versions, the Ansys Geometry service
requires a **Discovery Modeling** license to run.

To run PyAnsys Geometry against other backends, such as Discovery
or SpaceClaim, users must have an Ansys license that allows them to run these
Ansys products.

The **Discovery Modeling** license is one of these licenses, but there are others,
such as the Ansys Mechanical Enterprise license, that also allow users to run
these Ansys products. However, the Geometry service is only compatible with
the **Discovery Modeling** license.

.. button-ref:: index
    :ref-type: doc
    :color: primary
    :shadow:
    :expand:

    Go to Getting started
