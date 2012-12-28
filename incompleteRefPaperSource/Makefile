all: mapperIncRefTransPaper2012.pdf

clean:
	rm -f mapperIncRefTransPaper2012.pdf mapperIncRefTransPaper2012.bbl

mapperIncRefTransPaper2012.pdf: mapperIncRefTransPaper2012.tex
	pdflatex mapperIncRefTransPaper2012.tex
	pdflatex mapperIncRefTransPaper2012.tex
	bibtex mapperIncRefTransPaper2012
	pdflatex mapperIncRefTransPaper2012.tex
	pdflatex mapperIncRefTransPaper2012.tex
