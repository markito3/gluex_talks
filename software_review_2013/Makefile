FIGS = check_mark.png cpu_scaling.png farm_usage_2012.png grid_usage_2012.png new.jpg omega_peak.png flowchart.png

Hall_D_work_flow_data_challenges_MMI.pdf: Hall_D_work_flow_data_challenges_MMI.tex $(FIGS)
	xterm -e pdflatex $<

%.png: %.dia
	dia -e $@ $<
