# Beamer slide filenames (e.g., 2025_6_3.tex)
TEX_FILES := $(wildcard *.tex)
PDF_FILES := $(TEX_FILES:.tex=.pdf)

LATEX = pdflatex
LATEX_OPTS = -halt-on-error -interaction=nonstopmode

.PHONY: all clean

all: $(PDF_FILES)

%.pdf: %.tex
	$(LATEX) $(LATEX_OPTS) $<

clean:
	rm -f *.aux *.log *.nav *.out *.snm *.toc *.vrb *.pdf
