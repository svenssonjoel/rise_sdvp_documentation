DOCUMENT="main"

all:
	lualatex $(DOCUMENT).tex
	#bibtex $(DOCUMENT)
	#makeglossaries $(DOCUMENT)
	#lualatex $(DOCUMENT).tex
	lualatex $(DOCUMENT).tex

clean:
	rm -f *~ *out *log *aux *toc *bbl *blg *bcf *ptc *acn *acr *alg *idx \
		*run.xml *xdy *-blx.bib *.glo *.ist *lof *.glg *.gls *.synctex*

