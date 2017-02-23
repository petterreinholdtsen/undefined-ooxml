
There are several areas of the OOXML standard that fail to define what
parts of the content formatted using OOXML actually mean.  This
project aim to detect all documents containing such parts.

The motivation behind this project is to help archivers worldwide to
know if a given document claiming to follow the OOXML standard can be
understood by reading the OOXML specification, or if it depend on some
vendor specific behaviour that might be unavailable hundred years from
now.

The background is that the state archiver in Norway announced
2017-02-17 in
http://www.arkivrad.no/aktuelt/riksarkivarens-forskrift-pa-horing they
plan to allow OOXML documents to be archived (but only on request and
with special approval).  When deciding it approval should be given it
would be useful to know if the documents in question are well defined
in the OOXML specification.

The OOXML specification is filled with parts with undefined behaviour.
You can download the specification from
http://www.ecma-international.org/publications/standards/Ecma-376.htm
and search for 'application-de' yourself to find the
'application-defined' or 'application-dependent' parts.

The specification explain the relevant terms in part 1 section 4:

  behavior, implementation-defined — Unspecified behavior where each
  implementation is expected to document that behavior, which would
  thereby promote predictability and reproducibility within any given
  implementation. (This term is sometimes called “application-defined
  behavior”.)

  behavior, unspecified —Behavior where ECMA-376 makes no
  recommendations. (This term is sometimes called
  “application-dependent behavior”.) [Note: To add an extension, an
  implementer must use the extensibility mechanisms described by
  ECMA-376 rather than trying to do so by giving meaning to otherwise
  unspecified behavior. end note]

Some background information can be found in the document "The Case
Against OOXML",
<URL: http://noooxml.wdfiles.com/local--files/arguments/TheCaseAgainstOOXML.pdf >.
