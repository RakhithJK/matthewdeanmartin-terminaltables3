
Changelog
=========

This project adheres to `Semantic Versioning <http://semver.org/>`_.

3.1.7 - 2016-12-7
------------------

Added
    * Published wheel. Resume maintenance under new developer after main project had been archived.

3.1.0 - 2016-10-16
------------------

Added
    * ``git --porcelain``-like table by liiight: https://github.com/Robpol86/terminaltables/pull/31

3.0.0 - 2016-05-30
------------------

Added
    * Support for https://pypi.python.org/pypi/colorama
    * Support for https://pypi.python.org/pypi/termcolor
    * Support for RTL characters (Arabic and Hebrew).
    * Support for non-string items in ``table_data`` like integers.

Changed
- Refactored again, but this time entire project including tests.

Removed
- ``padded_table_data`` property and ``join_row()``. Moving away from repeated string joining/splitting.

Fixed

- ``set_terminal_title()`` Unicode handling on Windows.
- https://github.com/Robpol86/terminaltables/issues/18
- https://github.com/Robpol86/terminaltables/issues/20
- https://github.com/Robpol86/terminaltables/issues/23
- https://github.com/Robpol86/terminaltables/issues/26

2.1.0 - 2015-11-02
------------------

Added
    * GitHub Flavored Markdown table by bcho: https://github.com/Robpol86/terminaltables/pull/12
    * Python 3.5 support (Linux/OS X and Windows).

2.0.0 - 2015-10-11
------------------

Changed
    * Refactored code. No new features.
    * Breaking changes: ``UnixTable``/``WindowsTable``/``WindowsTableDouble`` moved. Use ``SingleTable``/``DoubleTable``
      instead.

1.2.1 - 2015-09-03
------------------

Fixed
    * CJK character width fixed by zqqf16 and bcho: https://github.com/Robpol86/terminaltables/pull/9

1.2.0 - 2015-05-31
------------------

Added
    * Bottom row separator.

1.1.1 - 2014-11-03
------------------

Fixed
    * Python 2.7 64-bit terminal width bug on Windows.

1.1.0 - 2014-11-02
------------------

Added
    * Windows support.
    * Double-lined table.

1.0.2 - 2014-09-18
------------------

Added
    * ``table_width`` and ``ok`` properties.

1.0.1 - 2014-09-12
------------------

Added
    * Terminal width/height defaults for testing.
    * ``terminaltables.DEFAULT_TERMINAL_WIDTH``
    * ``terminaltables.DEFAULT_TERMINAL_HEIGHT``

1.0.0 - 2014-09-11
------------------

* Initial release.

.. changelog-section-end
