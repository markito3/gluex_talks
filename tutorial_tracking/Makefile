all: tutorial_tracking_mmi.pdf

%.aux: %.tex
	pdflatex $*

%.pdf: %.aux
	pdflatex $*

display: tutorial_tracking_mmi.pdf
	evince tutorial_tracking_mmi.pdf &
