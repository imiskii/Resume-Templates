#
# Projekt: CV-lazy-style.tex
# Autor:   Michal Ľaš
# Datum:   28.05.2023
# 


NAME=CV-lazy-style

all: proj

proj: $(NAME).tex
	latex $(NAME).tex
	latex $(NAME).tex
	dvips -t -a4 $(NAME).dvi
	-sPAPERSIZE=a4 ps2pdf $(NAME).ps


clean:
	rm -f *.dvi
	rm -f *.ps
	rm -f *.aux
	rm -f *.out
	rm -f *.log
	rm -f *.gz
	rm $(NAME).pdf
