clean:
	rm -f out/document.pdf
	rm -f document.*
	rm -f tex/*.aux

all: tex/*.tex # bib/bibliography.bib
	pdflatex base/document.tex
	# bibtex document
	# pdflatex base/document
	# pdflatex base/document
	mv document.pdf pdf/document.pdf
	rm -f document.*
	rm -f tex/*.aux
