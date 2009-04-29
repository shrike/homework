.PHONY: clean

all: ps5.pdf

%.dvi: %.latex
	latex $<

%.pdf: %.dvi
	dvipdf $<

clean:
	rm -rf *log *pdf *dvi *aux
