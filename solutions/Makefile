fname = solutions
pdf:
	pdflatex $(fname)
	pdflatex $(fname)
	bibtex $(fname)
	pdflatex $(fname)
	pdflatex $(fname)
clean:
	rm -f $(fname).aux
	rm -f $(fname).bbl
	rm -f $(fname).blg
	rm -f $(fname).fdb_latexmk
	rm -f $(fname).fls
	rm -f $(fname).log
	rm -f $(fname).out
	rm -f $(fname).synctex.gz
	rm -f $(fname).pdf
	rm -f $(fname).toc

