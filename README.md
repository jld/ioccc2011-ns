Yet Another Obfuscated Sudoku Generator (spoiler-free repository)
=======================================

This was my submission to the 20th [International Obfuscated C Code
Contest] [IOCCC]; this repository contains only the contest
deliverables, without additional spoilers in the form of, e.g.,
development history, personal notes, or semi-obfuscated precursor
forms of the program.

The thing itself is in `final.c`; the accompanying `Makefile` may be
of use but is trivial.  The `remarks.md` file explains what the
program does and how to build and use it; it also explains how it does
that thing, and describes the ways in which that functioning is
obfuscated, but these sections were written vaguely enough that they
are not expected to be helpful in understanding the program.


Erratum
-------

The section of the remarks which documents the few known nasal demons
is incomplete; there is one more known environmental dependency which
I forgot about until several hours after the contest deadline.
However, it is satisfied by essentially every known C environment, and
I'm told that it may also be guaranteed by POSIX (as an extension of
ANSI C proper).



  [IOCCC]: http://www.ioccc.org
