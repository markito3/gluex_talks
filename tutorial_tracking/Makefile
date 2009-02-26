all: tutorial_tracking_mmi.pdf

%.aux: %.tex DParticle.png
	pdflatex $*

%.pdf: %.aux
	pdflatex $*

display: tutorial_tracking_mmi.pdf
	evince tutorial_tracking_mmi.pdf &
