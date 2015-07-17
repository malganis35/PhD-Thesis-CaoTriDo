Roque's Phd thesis template (for LaTeX) v0.1

Description
---------

This collection of LaTeX files is a Phd thesis template intended to
work with PDFLatex 2e. It includes the official title page from
Université de Grenoble and relies on an extensible structure. The
sample files are written in French but can be easily changed to
another language thanks to UTF-8 encoding and redefining few
variables.

Operating instruction
-----------------

Encoding : UTF-8
Latex compiler : PDFLatex
Verified on : Texlive-2011

The main file "roque-phdthesis.tex" can be compiled thanks to the
following procedure :
  pdflatex roque-phdthesis
  bibtex roque-phdthesis
  pdflatex roque-phdthesis
  pdflatex roque-phdthesis

Files from the subdirectories are used during the compilation process
(the subdirectory structure is described below).

Directory manifest
---------------

  0-configuration : packages loading and user's macros definitions.
  1-opening : title pages, acknowledgements, acronym tables. 
  2-chapters : introduction, chapters and conclusion.
  3-closing : abstract.
  4-appendices : zero or more chapters.
  images : includes images and illustrations.
  templates : includes the style files.

Credits and acknowledgements
------------------------

This template has been created by Damien Roque (GIPSA-lab)
<damien.roque@gipsa-lab.grenoble-inp.fr>.

The author would like to thank the anonymous guy from the G2ELab who
redesigned the official title page of Université de Grenoble.

Changelog
--------

  03/08/13 v0.1 Initial version

