.. _spikecell:

Spike source cells
==================

The description of a spiking cell controls the spiking schedule of the cell. Its morphology is
automatically modelled as a single :term:`compartment <control volume>`; each cell has one built-in **source** which does not need to
be explicitly added in the cell description, and no **targets**. Spiking cells do not support adding additional
**sources** or **targets**. They do not support **gap junctions**. They do not support adding density or
point mechanisms.

API
---

* :ref:`Python <pyspikecell>`
* :ref:`C++ <cppspikecell>`
