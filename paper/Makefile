paper.pdf: paper.tex references.bib
	pdflatex paper
	bibtex paper
	pdflatex paper
	pdflatex paper

clean:
	rm -f *.aux *.bbl *.blg *.log *.out *.toc paper.pdf *.cut
