Changelog
=========

0.3.0 (2011-3-02)
------------------

- Added module constants for the FSEvents event flags. These are built from the header file,
  so there is no duplication of the values from FSEvents.h
  [wynnw]

0.2.4 (2010-12-06)
------------------

- Prevent crashes on recursive folder delete and multiple folder add.
  [totolici].

0.2.3 (2010-07-27)
------------------

- Fixed broken release.

0.2.2 (2010-07-26)
------------------

- Python 2.4 compatibility [howitz]

- Fixed an issue where the addition of a new directory would crash the
  program when using file event monitoring [andymacp].

0.2.1 (2010-04-27)
------------------

- Fixed an import issue [andymacp].

0.2 (2010-04-26)
----------------

- Fixed issue where existing directories would be reported along with
  a newly created one [marcboeker].

- Added support for file event monitoring.

- Fixed reference counting bug which could result in a segmentation
  fault.

0.1 (2009-11-27)
----------------

- Initial public release.
