Minimum/maximum operations
==========================

.. role:: cppkokkos(code)
    :language: cpp

.. _StandarLibraryHeaderAlgorithm: https://en.cppreference.com/w/cpp/header/algorithm

.. |StandarLibraryHeaderAlgorithm| replace:: ``<algorithm>``

Defined in header ``<Kokkos_Core.hpp>``

Provides minimum/maximum and related operations from the standard library header |StandarLibraryHeaderAlgorithm|_.

The min/max and clamp function templates are defined in the ``Kokkos::`` namespace since Kokkos 3.7

.. _min: https://en.cppreference.com/w/cpp/algorithm/min

.. |min| replace:: ``min``

.. _max: https://en.cppreference.com/w/cpp/algorithm/max

.. |max| replace:: ``max``

.. _minmax: https://en.cppreference.com/w/cpp/algorithm/minmax

.. |minmax| replace:: ``minmax``

.. _clamp: https://en.cppreference.com/w/cpp/algorithm/clamp

.. |clamp| replace:: ``clamp``


========== ============================================================
|min|_     returns the smaller of the given values
|max|_     returns the greater of the given values
|minmax|_  returns the smaller and larger of the given values
|clamp|_   clamps a value between a pair of boundary values
========== ============================================================

----

See also
--------

.. _min_element: ../../algorithms/std-algorithms/all/StdMinElement.html

.. |min_element| replace:: ``min_element``

.. _max_element: ../../algorithms/std-algorithms/all/StdMaxElement.html

.. |max_element| replace:: ``max_element``

.. _minmax_element: ../../algorithms/std-algorithms/all/StdMinMaxElement.html

.. |minmax_element| replace:: ``minmax_element``

|min_element|_: returns the smallest element in a range

|max_element|_: returns the largest element in a range

|minmax_element|_: returns the smallest and the largest elements in a range

