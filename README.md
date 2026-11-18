# StudLab Shadow Library

This repository contains the StudLab Shadow Library, a collection of LDraw patch files, based on the [LDCad Shadow Library](https://github.com/RolandMelkert/LDCadShadowLibrary)  and [LDraw Parts Library](https://library.ldraw.org), which add snapping and connection information to LDraw parts and is used in the StudLab app. If you don't know what this is about, you should first check LDCad Shadow Library's readme file.

The StudLab Shadow Library complements the already existing LDCad Shadow Library by adding extra snapping and connection information from StudLab's own automatic estimator, and StudLab’s manually curated part information entries. We share the extended library under CC BY-SA 4.0, following the original library’s licence, in case it is useful to LDCad users or developers of LDraw-related software.

## Using the library

The files use standard LDCad snap commands. The library is created by combining information already present in the LDCad Shadow Library with other information provided by StudLab's automatic estimator and manual corrections, which requires a rather complex merging process. For that reason, we mostly provide part-specific `.dat` files. Direct use of this library in LDCad should be possible, but it is untested.

The library contains 25983 files, including 24981 resolved part files and 1002 reusable entries. The `parts/` folder holds part and subpart files, and `p/` holds primitive files. Comments identify the source of the connections and can be ignored by compatible readers.

## Source versions

- LDCad Shadow Library commit · [`9b1131fb1991f8c0bfc072325e4e12f6271aba35`](https://github.com/RolandMelkert/LDCadShadowLibrary/commit/9b1131fb1991f8c0bfc072325e4e12f6271aba35)
- LDraw Parts Library release · 2026-10

## Licence

CC BY-SA 4.0. See `LICENSE.md`. The library incorporates the LDCad Shadow Library’s entries by Roland Melkert and its contributors and uses geometry from the LDraw Parts Library.
