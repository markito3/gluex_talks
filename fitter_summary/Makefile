all: fitter_summary.pdf

%.aux: %.tex
	pdflatex $*

%.pdf: %.aux
	pdflatex $*

display: fitter_summary.pdf
	evince $< &
