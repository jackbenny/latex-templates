lab:
	cat lab.tex | sed 's/Lab report X/Lab report $(LAB)'/ > lab$(LAB).tex
	pdflatex lab$(LAB).tex
clean:
	rm *.aux
	rm *.log
	rm *.out
	rm *.toc
	rm *.pdf
