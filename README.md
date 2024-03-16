# essential_utilities_miscellaneous

Essential miscellaneous utilities


1) Combining multiple pdf files on Linux (adapted from link)

use gs (ghostscript)

gs -dBATCH -dNOPAUSE -q -sDEVICE=pdfwrite -sOutputFile=finished.pdf *.pdf


Also available on bitbucket

PDF splitter

#!/bin/sh
#
# https://stackoverflow.com/questions/10228592/splitting-a-pdf-with-ghostscript
#
# pdfsplit [input.pdf] [first_page] [last_page] [output.pdf]
#
# Example: pdfsplit big_file.pdf 10 20 pages_ten_to_twenty.pdf
#
# written by: Westley Weimer, Wed Mar 19 17:58:09 EDT 2008
#
# The trick: ghostscript (gs) will do PDF splitting for you, it's just not
# obvious and the required defines are not listed in the manual page.

if [ $# -lt 4 ]
then
        echo "Usage: pdfsplit input.pdf first_page last_page output.pdf"
        exit 1
fi
gs -dNOPAUSE -dQUIET -dBATCH -sOutputFile="$4" -dFirstPage=$2 -dLastPage=$3 -sDEVICE=pdfwrite "$1"

2) Editors for code (vi and Sublime Text)

3) Tools for diff (FileMerge on Mac OS X)

4) Mirador for quick data science on data

5) Awesome latex CV template, Rmarkdown CV template

6) Virtual machines (VirtualBox) and run Ubuntu UNIX in the VM

         Download the Ubuntu ISO file here

7) Getting MAC addresses:

    Windows: run command prompt (Start -> cmd), then: ipconfig /all

    Linux, own machine, e.g: ifconfig -a

    Linux, other machine, e.g.: arping -f -I eth1 ipaddress 

8) Augmenting cognition by Michael Nielsen (link)

9) Image/diagram/figure manipulation and editing using Gimp, Inkscape, photopea

       these are open source and free alternatives to Adobe Illustrator

       http://draw.io (link)

       https://sketch.io/sketchpad

       https://biorender.com/  (for making biological drawings and graphical abstracts)

       TikZ Latex program for drawing shapes (overleaf)

10) Password manager (link)

         Best to generate passwords in the browser KeeWeb (link) (link)

         KeePass desktop client

         list by WIRED  

11) Online equation editor (link)

Online latex equation (link)

12) Online symbolic equation solver (link) (link)

13) Games

Passage video game by Rohrer

Space invaders retro video game
