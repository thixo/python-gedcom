A python module for parsing, analyzing, and manipulating GEDCOM files.

GEDCOM files contain ancestry data, the GEDCOM 5.5 format is detailed here:
http://homepages.rootsweb.ancestry.com/~pmcbride/gedcom/55gctoc.htm

This module was originally based on a GEDCOM parser written by 
Daniel Zappala at Brigham Young University (copyright (C) 2005) and 
was licensed under GPL v2.

Extended with PlaceElement to allow for:
* updating values (e.g. "Bp Auckland" to "Bishop Auckland")
* adding a choice of geographic information from Ordnance Survey gazetteer
* recording which gazetteer entry is correct
