source=presentation_2

all:
	latex $(source).tex
	latex $(source).tex
	dvipdf $(source).dvi
	make clean

clean:
	rm -f *.aux *.dvi *.log *.toc
