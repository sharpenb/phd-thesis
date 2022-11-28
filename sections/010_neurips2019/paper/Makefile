TEX = pdflatex

.PHONY: all view clean

all : nips_2019.pdf

view :
	evince nips_2019.pdf

clean :
	rm nips_2019.pdf *.log *.aux *.out *.dvi

nips_2018.pdf : nips_2019.tex
	$(TEX) nips_2019.tex
