=======
History
=======

0.1.4 (unreleased)
------------------

- Add support for multipolygon.
- Remove the ``fill_hole`` argument.

0.1.3 (2020-08-18)
------------------

- Replaced ``simplejson`` with ``orjson`` to speed-up JSON operations.

0.1.2 (2020-08-11)
------------------

- Add ``show_versions`` for showing versions of the installed deps.

0.1.1 (2020-08-03)
------------------

- Retained the compatibility with ``xarray`` 0.15 by removing the ``attrs`` flag.
- Replaced ``open_dataset`` with ``load_dataset`` for automatic handling of closing
  the input after reading the content.
- Removed ``years`` argument from both ``byloc`` and ``bygeom`` functions. The ``dates``
  argument now accepts both a tuple of start and end dates and a list of years.

0.1.0 (2020-07-27)
------------------

- Initial release on PyPI.
