==================
CalligraConverter
==================

----------------------------
Calligra Document Converter
----------------------------

:Author: This manual page was written by Adrien Grellier <perso@adrieng.fr> for the Debian project (but may be used by others).
:Date: |date|
:Manual section: 1
:Manual group: office

Synopsis
========

calligraconverter [Qt-options] [KDE-options] in out 

Description
===========

Legacy integer arithmetics implementation 

Options
=======

Arguments:

**in**                        Input file
**out**                       Output file

Options:

--backup                    Make a backup of the destination file
--batch                     Batch mode: do not show dialogs
--interactive               Interactive mode: show dialogs (default)
--mimetype <mime>           Mimetype of the output file
--print-orientation <name>  The print orientation. This could be either Portrait or Landscape.
--print-papersize <name>    The paper size. A4, Legal, Letter, ...
--print-margin <size>       The size of the paper margin. By default this is 0.2.

Generic options:

--help                    Show help about options
--help-qt                 Show Qt specific options
--help-kde                Show KDE specific options
--help-all                Show all options
--author                  Show author information
-v, --version             Show version information
--license                 Show license information

SEE ALSO
=========

More detailed user documentation is available from **help:/calligra** (either enter this URL into Konqueror, or run **khelpcenter** *help:/calligra*).



.. |date| date:: %y %B %Y
