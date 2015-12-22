_**Notice:** I no longer maintain this project, having developed my own documentation software
from scratch, called [FORD](https://github.com/cmacmackin/ford)._

This is f03doc version 0.1.0, a documentation tool for Fortran 2003.  It is an
extension of f90doc 0.4.0, allowing it to handle the various object oriented 
and C interoperability features in the Fortran 2003 standard.  For
more information on f90doc (e.g., documentation), see 
http://theory.lcs.mit.edu/~edemaine/f90doc or contact Erik Demaine 
(edemaine@mit.edu).  For questions on the f03doc 
modifications, please contact Chris MacMackin through the GitHub page at
https://github.com/cmacmackin/f03. Bug reports are also welcome 

#Copyright

f03doc is free software.  If you use it in a research or commercial project, you
must acknowledge the software and its authors.  If you base code on
f90doc, you must acknowledge this.

This information must accompany any copy of f03doc.

#Installation

The source is available from GitHub:

    git clone https://github.com/cmacmackin/f03doc

You shouldn't have to compile anything.  You can put the file f03doc in
a more accessible place, but the .pl files have to be in the same directory.
Alternatively, you can create a symlink to the real f03doc, where the .pl
files are held.  For example,
    
    ln -s /usr/local/lib/f03doc/f03doc /usr/local/bin/f03doc

If you don't have a command /usr/bin/env, you'll need to replace the first line
of f03doc with

    #!/path/to/perl5/bin/perl -w

Otherwise, Perl version 5.003 or higher must be the first program called "perl"
in your path.
