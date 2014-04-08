ish
===

Inventory shell to browse files offline using unix-like commands


Ish is a bash script that presents a shell to the user to create and
access inventory files (or index files) that contain a list of file
with meta data (date, size, etc.).  The access mimics aspects of a
unix-like shell.  The intended use of ish is to keep track of data
stored at various locations and files systems.  The current version
of ish is 0.997.

ish is open-source, and is released under the MIT license. This
library is distributed WITHOUT ANY WARRANTY. For details, see the file
named 'LICENSE', and license statements in the source files.

Installation
============

Ish is written in bash and will thus need a relative recent version of
bash.  Copying the script called "ish" to a location in your PATH will
be enough to install it.

Ish has been tested with bash version 4.1.2, and some earlier
versions.  Bash version 3.2.16 is known to have some issues with parts
of the script.  A number of utilities such as zgrep, zdiff, tar,... 
are also needed.  Apologies for there not being an exhaustive list
of prerequisites yet; this one reason why this is still version 0.997.

Documentation
=============

Ish contains a near-complete documentation system through its help
command. "ish help" gives a list of all ish commands. "ish help CMD",
where CMD is one of those ish commands, gives a detailed 'manpage' for
that ish command.  It is highly recommanded to read this
documentation, especially since many ish commands resemble commands in
bash and other unix-like shells, but are not precisely the same
in functionality or in syntax.

Reporting Bugs
==============

Under the license, you are not required to report bugs, but are
encouraged to do so.  If you find a bug, you may report it to
rzon@scinethpc.ca or vanzonr@gmail.com. Errors or omissions in the
help can be reported to the same address.

Files
=====

ish:                The application, written in bash.

WARRANTEE:          File that expresses that there is no warrantee

LICENSE:            Text of the MIT license

AUTHOR:             Name and email address of the author

README.md:          This file

- 8 April 2014 
