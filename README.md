Graph matching
==============

This file was last updated on November 12, 2014.

Downloading
-----------

This paper can be found at https://github.com/jfinkels/graphmatching.

To download the paper using [Git][1], run

    git clone git@github.com:jfinkels/graphmatching.git

A somewhat recent version of this work should be available at
https://cs-people.bu.edu/jeffreyf#graphmatching, but I can't guarantee that it
will always be up to date, since I compile and upload it manually.

[1]: http://git-scm.com

Compilation dependencies
------------------------

This document requires `pdflatex` to compile and `biber` for bibliography
management. The complete list of LaTeX packages required to compile this
document can be found at the head of the file `graphmatching.tex`.

To install the necessary packages on Ubuntu, run

    sudo apt-get install texlive-base texlive-latex-base texlive-latex-extra \
      texlive-science biber

Compiling
---------

To compile the document, run

    pdflatex graphmatching
    biber graphmatching
    pdflatex graphmatching

The output is `graphmatching.pdf`, and can be viewed with any PDF reader.

Copyright
---------

Copyright 2014 Jeffrey Finkelstein.

Both the LaTeX markup and the compiled document are made available under the
terms of the Creative Commons Attribution-ShareAlike 4.0 International License,
https://creativecommons.org/licenses/by-sa/4.0/.

Contact
-------

Jeffrey Finkelstein <jeffrey.finkelstein@gmail.com>
