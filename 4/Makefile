proj4.pdf: proj4.ps
	ps2pdf -sPAPERSIZE=a4 proj4.ps
proj4.ps: proj4.dvi
	dvips -t a4 proj4.dvi
proj4.dvi: proj4.tex
	latex proj4.tex
	bibtex proj4
	latex proj4.tex
	latex proj4.tex