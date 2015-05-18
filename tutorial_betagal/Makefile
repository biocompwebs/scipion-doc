# Pass pdflatex a couple of times to fix the labels and references.

all: betagal.tex
	pdflatex betagal.tex
	bibtex betagal.aux
	pdflatex betagal.tex
	pdflatex betagal.tex
