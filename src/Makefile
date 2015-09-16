all:
	pdflatex example.tex
	pdflatex example.tex
	rm -f *.log
	rm -f *.toc
	rm -f `ls | grep -E "example.[^ (bib|tex|pdf)]"`
