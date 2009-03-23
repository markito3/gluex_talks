all: pulls_resids.pdf

%.aux: %.tex
	pdflatex $*

%.pdf: %.aux
	pdflatex $*

display: fitter_summary.pdf
	evince $< &
