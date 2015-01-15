# Pass pdflatex a couple of times to fix the labels and references.

all: initialvolume.tex
	pdflatex initialvolume.tex
	bibtex initialvolume.aux
	pdflatex initialvolume.tex
	pdflatex initialvolume.tex
