## CeeVeeTex
Template to create a Curriculum Vitae. There is also a template for a cover/motivation letter.  

### Content details
Actually, 3 templates are presented (6 in total, counting the ones that include a photo).  
* The main and somehow graphically better is [`CeeVeeTex.tex`](./CeeVeeTex.tex).  
  * One version of this first template that includes links to web content pages, embedded in logos, is [`CeeVeeTex_w_links.tex`](./CeeVeeTex_w_links.tex).  
* Then, there is a simplified version, called [`CeeVeeTex_simple.tex`](./CeeVeeTex_simple.tex).  
This latter one is derived from the first, but with a sipler graphical arrangement.  
* Moreover, a CV based on the _europecv_ class is present. This is somehow a standard in Europe, and the document class is well implemented and documented in texlive (the package I've use to create these Latex documents).  

### Bonus
As a real example of CV, I included the `.tex` and the relative `.pdf` output of my currently up-to-date CV (most of the personal details have been stripped). It's called [`mz_CeeVeeTex_noinfo.tex`](./mz_CeeVeeTex_noinfo.tex).  

----

Created with Texlive in Manjaro 26.1.0:
```
❯ pdflatex --version
pdfTeX 3.141592653-2.6-1.40.29 (TeX Live 2026/Arch Linux)
kpathsea version 6.4.2
Copyright 2026 Han The Thanh (pdfTeX) et al.
There is NO warranty.  Redistribution of this software is
covered by the terms of both the pdfTeX copyright and
the Lesser GNU General Public License.
For more information about these matters, see the file
named COPYING and the pdfTeX source.
Primary author of pdfTeX: Han The Thanh (pdfTeX) et al.
Compiled with libpng 1.6.58; using libpng 1.6.58
Compiled with zlib 1.3.2; using zlib 1.3.2
Compiled with xpdf version 4.06
```
