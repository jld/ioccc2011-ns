Yet Another Obfuscated Sudoku Generator (spoiler-free repository)
=======================================

This was my submission to the 20th [International Obfuscated C Code
Contest] [IOCCC]; this repository contains only the contest
deliverables, without additional spoilers in the form of, e.g.,
development history, personal notes, or semi-obfuscated precursor
forms of the program.

  [IOCCC]: http://www.ioccc.org

The thing itself is in `final.c`; the accompanying `Makefile` may be
of use but is trivial.  The `remarks.md` file explains what the
program does and how to build and use it; it also explains how it does
that thing, and describes the ways in which that functioning is
obfuscated, but these sections were written vaguely enough that they
are not expected to be helpful in understanding the program.

It lost.


Copying
-------

This program is released into the public domain, as required by the
IOCCC submission rules.  Specifically, I release it under [CC0],
although that license and the beginning of this paragraph are
equivalent up to the noninvolvement of lawyers.

Of course, as a losing entry, its existence will be steadfastly denied
by the IOCCC organizers — also as specified by the contest rules — so
I suppose I could theoretically turn around and claim copyright
interest on it and they couldn't stop me.  But if I did that, then I'd
effectively also be denying that it was an IOCCC entry, which kind of
defeats the point.

So, public domain it is.  Indeed, if anyone finds a way to make use of
this, I might actually prefer not to be publicly associated with the
result in any way.

  [CC0]: http://creativecommons.org/publicdomain/zero/1.0/


Erratum
-------

The section of the remarks which documents the few known nasal demons
is incomplete; there is one more known environmental dependency which
I forgot about until several hours after the contest deadline.
However, it is satisfied by essentially every known C environment, and
I'm told that it may also be guaranteed by POSIX (as an extension of
ANSI C proper).
