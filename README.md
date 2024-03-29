FOGTeX
======

This repository will contain PHP and LaTeX files for creating Field Operations
Guides (FOGs). Users, using the HTML pages generated by the PHP scripts, will
be able to create their own custom FOGs containing only the sections they want
in their FOG.

This project was created out of fraustration to find the perfect FOG. While
FOGs that contained great information existed, many contained information that
the creator did not need and lacked information that was needed. Being a
candidate for OCD, the creator did not want to simply print particular pages
from different FOGs (as would stuff up the page numbering), so created this
project in the hope the others were wanting the same thing.

FOGTeX Document Class
======

The FOGTeX document class enables the generation of ready-to-print FOG cards.
The two sizes of card that are currently supported are (W x H):
* 80mm x 100mm - Pocket-sized FOG
* 90mm x 55mm - Business card sized FOG

The pocket-sized FOG is able to be printed four to a sheet of A4 paper, cut and
then laminated using an A4-sized laminate sleeve.

The document class will generate the pages laid out in the order so they can be
printed on a duplex printer (flipping long edge) and be correctly ordered.

FOGTeX Parts
======
The parts folder contains all the TeX files containing parts of the FOG.

Each file can be split up into multiple sections that can be included
individually or as a whole using TeX docstrip tags. Sections can be wrapped in
multiple docstrip tags allowing for hierarchical inclusion schemes.

All TeX files located in the parts folder will be scanned and parsed by the PHP
scripts 


PHP Scripts
======

TODO

