all: ccdb_intro.pdf

ccdb_intro.png: ccdb_intro.fig
	$(RM) $@
	fig2dev -L png -m 4 $< > $@

ccdb_intro.pdf: ccdb_intro.tex ccdb_intro.png
	pdflatex $<
	pdflatex $<

clean:
	$(RM) *.aux ccdb_intro.pdf *.log *.tmp ccdb.png
