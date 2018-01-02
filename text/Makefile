FILE=adam-laza-dp-2018

all:
	pdflatex $(FILE)
	bibtex $(FILE)

clean:
	rm -f *~ *.aux *.log *.out *.bbl *.blg *.loa *.lof \
	*.toc *.lot

distclean:
	make clean
	rm -f $(FILE).pdf
