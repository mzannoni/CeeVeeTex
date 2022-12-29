## CeeVeeTex
Template to create a Curriculum Vitae. There is also a template for a cover/motivation letter.  

### Content details
Actually, 3 templates are presented.  
* The main and somehow graphically better is [`CeeVeeTex.tex`](./CeeVeeTex.tex).  
  * One version of this first template that includes links to web content pages, embedded in logos, is [`CeeVeeTex_w_links.tex`](./CeeVeeTex_w_links.tex).  
* Then, there is a simplified version, called [`CeeVeeTex_simple.tex`](./CeeVeeTex_simple.tex).  
This latter one is derived from the first, which has been created more or less from scratch.  
* Moreover, a CV based on the _europecv_ class is present. This is somehow a standard in Europe, and the document class is well implemented and documented in texlive (the package I've use to create these Latex documents).  

### Bonus
As a real example of CV, I included the `.tex` and the relative `.pdf` output of my currently up-to-date CV (most of the personal details have been stripped). It's called [`mz_CeeVeeTex_noinfo.tex`](./mz_CeeVeeTex_noinfo.tex).  

### Notes
The Latex source file are not yet clean from warnings (mainly, underfull/overfull badnesses). Any help/comment/tip on how to correct them, or in general on how to improve this repository are gladly welcome.  

----

Created with Texlive in Ubuntu 22.04:
```
❯ pdflatex -version
pdfTeX 3.141592653-2.6-1.40.22 (TeX Live 2022/dev/Debian)
kpathsea version 6.3.4/dev
Copyright 2021 Han The Thanh (pdfTeX) et al.
There is NO warranty.  Redistribution of this software is
covered by the terms of both the pdfTeX copyright and
the Lesser GNU General Public License.
For more information about these matters, see the file
named COPYING and the pdfTeX source.
Primary author of pdfTeX: Han The Thanh (pdfTeX) et al.
Compiled with libpng 1.6.37; using libpng 1.6.37
Compiled with zlib 1.2.11; using zlib 1.2.11
Compiled with xpdf version 4.03
```
