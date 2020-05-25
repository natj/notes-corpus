all:
	pdflatex notes
	pubs export > refs.bib
	bibtex notes
	pdflatex notes
	pdflatex notes
	#dvips paper1
	#ps2pdf paper1
	#rm *.{aux,bbl,blg,d,dvi,log}
	rm *-eps-converted-to.pdf
