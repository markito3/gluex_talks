all: tutorial_tracking_mmi.pdf

%.pdf: %.tex
	pdflatex $<
	pdflatex $<

display: tutorial_tracking_mmi.pdf
	evince tutorial_tracking_mmi.pdf &
