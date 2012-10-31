

SOURCE=swarm

all:
	pdflatex $(SOURCE)
	bibtex $(SOURCE)
	pdflatex $(SOURCE)
	pdflatex $(SOURCE)

clean:
	rm -f *.dvi *.log $(SOURCE).blg $(SOURCE).bbl $(SOURCE).toc *.aux $(SOURCE).out $(SOURCE).lof $(SOURCE).nav $(SOURCE).snm
	rm -f $(SOURCE).pdf

