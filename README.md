## Resume

A compact **two column, one page colour** Latex Resume. It can also be used as a template. The file `cv.pdf` is the output of these tex files.

### Features

* Two column format
* Single page 
* Vivid purple - grey colours used


#### Dependencies
* AltaCV uses [`fontawesome`](http://www.ctan.org/pkg/fontawesome) and [`academicons`](http://www.ctan.org/pkg/academicons)
* Loading `academicons` is optional: can be enabled it by adding the `academicons` option to `\documentclass`.
* Can be compiled with pdflatex, XeLaTeX and LuaLaTeX.
* However if you're using `academicons`, you _must_ use either XeLaTeX or LuaLaTeX. If the doc then compiles but the icons don't show up in the output PDF, try compiling with LuaLaTeX instead.
* The one here uses the [Lato](http://www.latofonts.com/lato-free-fonts/) font.

#### Issues
* Overflows onto second page if the contents of a column exceeds the vertical limit

##### License 

The LaTeX Project Public License
LPPL Version 1.3c 2008-05-04

##### Credits

 Marissa Meyer's BusinessInsider Resume and Overleaf's tex stylist


