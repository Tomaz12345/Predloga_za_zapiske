# Predloga za zapiske

Predloga za urejanje zapiskov s predavanj ali vaj

## Struktura

### bibtex

- za vse *.bib* datoteke, torej predvsem literatura

### images

- vse potrebne slike
- do njih se dostopa z *\includegraphics*, lahko naprej gnezdimo in dostopamo z relativno potjo

### main

- glavni del zapiskov - "ogrodje"
- v *main.pdf* vključenih precej (matematičnih) knjižnic, ki jih pogosto potrebujemo

### scripts

- trenutno samo *compile_all.py*; za prevedbo v *.pdf*, zažene enkrat *pdflatex*, enkrat *bibtex* in dvakrat *pdflatex* - da so vse reference ustrezne
- požene se v mapi *scripts*, 1. argument je ime glavne *.tex* datoteke brez končnice *.tex*
- primer: *python compile_all.py main*

### tex_files

- za *.tex* datoteke, kjer hranimo vsebino, npr. poglavja
- brez dodatnih *include*, *input* ... in brez *premable*