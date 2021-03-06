--------------------
eliot-tree changelog
--------------------

.. towncrier release notes start

Eliottree 18.1.0 (2018-07-30)
=============================

Features
--------

- Timestamps are now rendered after the action status or message level. A duration is included too when available. (#72)


Eliottree 18.0.0 (2018-07-23)
=============================

Features
--------

- Exceptions that occur during node or value formatting no longer interrupt processing and are displayed after the tree output. (#69)


Eliottree 17.1.0
==========

Bugfixes
--------

- Fixed an incompatibility with iso8601 0.1.12. (#60)


Eliottree 17.0.0
==========

Bugfixes
--------

- Python 3 compatibility was improved. (#35)
- Human-readable values are now only transformed at render time instead of
  mutating the log data. (#39)

Features
--------

- The `tree-format` library is now used for rendering the tree and colored
  output was added. (#19)
- Command-line options `--start` and `--end` were introduced to allow more
  easily specifying a time range of messages. (#38)
- Context is now reported when JSON or Eliot parse errors occur. (#42)
- Terminal control characters in Eliot data are now converted to their
  innocuous Unicode control image equivalent. (#44)
- Eliot's robust builtin parser is now used to build the tree data. (#52)

Misc
----

- #46, #54, #56


